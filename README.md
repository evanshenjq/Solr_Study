# Solr_Study
study for solr

## solr基础指令

solr_install/bin

solr start                开启solr

solr restart -p port      solr重启

solr stop -p port         solr停止

solr create -c core_name  创建一个solr内核

java -Dc='core_name' -jar post.jar file_path ## Windows引入索引文档

java -jar post.jar -help  ## post.jar帮助

./post -c 'core_name' file_path              linux引入索引文档
