## tag相关的命令

### 查询最新的tag
```bash
git describe --tags --abbrev=0
```

### 删除指定的tag
```bash
git tag -d <tag-name>
git push origin --delete <tag-name>
```

### 打tag
```bash
git tag <tag-name>
git push origin <tag-name>
```
