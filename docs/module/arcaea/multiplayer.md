# 多人游戏
<span class="span-group">群聊</span>

---

## 创建房间
```
/a mp create
```

## 加入房间
```
/a mp join <房间 ID>
```

::: tip 注意
您不能加入其他群聊创建的房间。
:::

## 设置完成状态
> 您需要在一个开始回合的房间中。
```
/a mp done
```

## 统计成绩
> 该指令仅房主可用。
```
/a mp upload [force]
```
`[force]` 存在时强制统计成绩（无视未完成的玩家）。

## 房间状态
> 您需要在一个房间中。
```
/a mp stat
```

## 退出房间
> 您需要在一个房间中。
```
/a mp exit
```

## 结束房间
> 该指令仅房主可用。
```
/a mp end
```