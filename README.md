# TypeScriptConfigStudy
TS 学习 - ts配置学习

- 在根目录只有一个ts文件的时候 直接运行 tsc 命令的时候，tsc会直接编译这个ts文件
- 这是因为执行tsc的时候，tsc会去检查tsconfig.json文件，文件中没有明确的声明要编译哪个文件，就会去编译根目录中的文件

includes 
encludes
files

- 直接执行tsc文件 他会使用tsconfig.json 文件中的配置
- 如果 执行tsc xxx.ts tsc会使用自己默认的配置文件
- 执行 ts-node xxx.ts ts-node 会使用项目中tsconfig.json 的配置