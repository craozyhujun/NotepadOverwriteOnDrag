# NotepadOverwriteOnDrag
20220508：在原生TextView的基础上重写了onLongClick和onDrag；onLongClick return true mean 冲突问题复现不响应 return false 交给原生处理；onDrag什么都不写 return true 不拖拽 return false交给原生处理可以拖拽 重写后 true响应拖拽事件原生逻辑 false就只响应drop里的逻辑 原生不响应了
