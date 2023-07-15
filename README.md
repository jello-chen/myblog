# myblog
- framework: hugo extended
- theme: fuji
## build
1. 本地启动：
   ```
   hugo server -t fuji --buildDrafts
   ```
2. 新建文章
   ```
   hugo new post/blog.md
   ```
3. 构建
   ```
   hugo -t fuji -b "https://jello-chen.github.io/" -D
   ```
