配置具体可见：[merge-branch.yml](./.github/workflows/merge_branch.yml)

- 同步时间：action 8-23点每3个小时去同步主库(PS：可自定义同步时间)
- 同步方法：action拉取主库到master分支，然后master分支再合并到main分支

**注意**：可以在main分支添加自己的文件，但最好不要修改主库的代码，以免同步（合并）代码失败
