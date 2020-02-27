# infer
[infer run shell](http://yuqiangcoder.com/2020/02/26/infer.html)

# 基础用法

1. 把 `infer.sh` 文件放在 `projectname.xcworkspace` 的同级目录；
2. 运行脚本 `./infer.sh`

# 高级用法

1. 对比分支间存在差异的文件
    
    ```
    ./infer.sh -s source_branch -t target_branch
    ```
    
2. 若当前分支为 `target_branch` 分支

    ```
    ./infer.sh -s source_branch
    ```
    
3. 若当前分支为 `source_branch` 分支

    ```
    ./infer.sh -t target_branch
    ```
    
4. 指定 xcworkspace 项目名称
    
    ```
    ./infer.sh -p project_name
    ```
    
5. 删除infer的输出结果
    
    ```
    ./infer.sh -d
    ```

6. 查看参数选项
    
    ```
    ./infer.sh -h
    ```

