# Test

```powershell
hugo new p1/intro.md
# lookup api.md under archtypes/api.md archtypes/default.md themes/xxx/archtypes/api.md themes/xxx/archtypes/default.md
hugo new --kind api p1/api.md
hugo new --kind example p1/example.md

hugo new p2/intro.md
hugo new --kind api p2/api.md
hugo new --kind example p2/example.md

hugo new --kind api p1/api.zh.md
```
