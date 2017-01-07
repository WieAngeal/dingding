```
服务器:{HOST.NAME}: {TRIGGER.NAME}已恢复!

{
"告警主机":"{HOST.NAME}",
"告警地址":"{HOST.IP}",
"告警时间":"{EVENT.DATE} {EVENT.TIME}",
"恢复时间":"{EVENT.RECOVERY.DATE} {EVENT.RECOVERY.TIME}",
"告警等级":"{TRIGGER.SEVERITY}",
"告警信息":"{TRIGGER.NAME}",
"监控项目":"{ITEM.NAME}",
"当前状态":"{TRIGGER.STATUS}",
"持续时间":"{EVENT.AGE}",
"事件ID":"{EVENT.ID}"
"监控取值":"{ITEM.LASTVALUE}"
}

服务器:{HOST.NAME}发生: {TRIGGER.NAME}故障!

{
"告警主机":"{HOST.NAME}",
"告警地址":"{HOST.IP}",
"告警时间":"{EVENT.DATE} {EVENT.TIME}",
"告警等级":"{TRIGGER.SEVERITY}",
"告警信息":"{TRIGGER.NAME}",
"监控项目":"{ITEM.NAME}",
"当前状态":"{TRIGGER.STATUS}",
"持续时间":"{EVENT.AGE}",
"事件ID":"{ITEM.ID}",
"监控取值":"{ITEM.LASTVALUE}"
}
```