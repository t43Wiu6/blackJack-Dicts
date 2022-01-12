# blackJack Dicts

参考自`burp、dirsearch、dirmap、sec-list、Web-Fuzzing-Box、fuzzDicts、Blasting_dictionary`等十余个项目的目录和文件字典

根据过时、重复、适用性弱、等原则整合修改得到本项目

## dir

`dir_mini`, 维持在2000+左右的纯目录字典
`dir`, 维持在5000+左右的纯目录字典
`dir_bigger`, 集成后整合的原字典, `25000`条

## api

`api/per_root_api`, 每个站点根目录枚举一次，用于发现api端点
`api/api_fuzz`, 当发现`api`目录时调用，用于fuzz以发现更多api端点 （爬自zoomeye）

## file

`file/per_root_file`, 每个站点根目录都枚举一次，用于寻找备份文件
`file/per_dir_file_replace`, 每个子目录都枚举一次，用于动态寻找备份文件，根据目录名生成

## asp

`asp/asp_dir`, 当发现`asp`相关指纹时调用，用于发现更多asp页面
`asp/asp_file`, 当发现`asp`相关指纹时调用，用于对于单个目录进行详细枚举

## aspx

`aspx/asp_dir`, 当发现`aspx`相关指纹时调用，用于发现更多aspx页面
`aspx/asp_file`, 当发现`aspx`相关指纹时调用，用于对于单个目录进行详细枚举

## java

`java/action_dir`, 当发现`java`框架相关指纹时调用，用于发现更多action路由
`java/action_file`, 当发现`java`框架相关指纹时调用，用于对于单个目录进行详细枚举

## jsp

`jsp/jsp_dir`, 当发现`jsp`相关指纹时调用，用于发现更多jsp页面
`jsp/jsp_file`, 当发现`jsp`相关指纹时调用，用于对于单个目录进行详细枚举

## php

`php/php_dir`, 当发现`php`相关指纹时调用，用于发现更多php页面
`php/php_file`, 当发现`php`相关指纹时调用，用于对于单个目录进行详细枚举

