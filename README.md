# Solr_Study
study for solr

## solr基础指令

solr_install/bin

solr start  |   开启solr 

solr restart -p port  |   solr重启    

solr stop -p port     |   solr停止  

## solr内核

solr create -c core_name  |	创建一个solr内核

solr delete -c core_name  | 删除solr内核

## solr引入文档

java -Dc='core_name' -jar post.jar file_path  | Windows引入索引文档(默认是xml,其他格式需要-Dtype)

java -jar post.jar -help   | post.jar帮助

./post -c 'core_name' file_path  |  linux引入索引文档
