<!-- 
  ███████╗ ██████╗  ██████╗██╗  ██╗██╗███╗   ██╗███████╗
  ██╔════╝██╔═══██╗██╔════╝██║  ██║██║████╗  ██║██╔════╝
  █████╗  ██║   ██║██║     ███████║██║██╔██╗ ██║█████╗  
  ██╔══╝  ██║   ██║██║     ██╔══██║██║██║╚██╗██║██╔══╝  
  ██║     ╚██████╔╝╚██████╗██║  ██║██║██║ ╚████║███████╗
  ╚═╝      ╚═════╝  ╚═════╝╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝╚══════╝
-->
# 🕶️ 9Insomnie | 红队渗透专家 | 永动机型失眠患者 

[![HTB](https://img.shields.io/badge/HackTheBox-Machine%20Master-red?logo=Hack%20The%20Box)](https://app.hackthebox.com/profile/1983709)
[![咖啡计量](https://img.shields.io/badge/咖啡因浓度-足以黑进卫星系统-critical)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

**专业制造甲方危机感 | 擅长将WAF变成装饰品 | 业余时间教防火墙做人**

``` 
  ╭━┳━╭━╭━╮╮
  ┃┈┈┈┣▅╋▅┫┃  ← 正在绕过你的安全策略
  ╰┳┻┻┻┻┻┻┻╯
   ▔▔▔▔▔▔▔▔
```

---

## 🔥 武器库（不断进化中）

[![红队工具链](https://skillicons.dev/icons?i=py,bash,powershell,aws,azure,docker,raspberrypi,linux&theme=dark&perline=8)]

**核心技能**  
```python
def night_ops():
    绕过EDR()
    种植持久化后门()
    while 未被发现:
        横向移动()
        数据渗出()
```

**装备清单**  
- **C2框架**: Cobalt Strike / Sliver / Mythic
- **魔法书**: 《内网渗透的100种体位》
- **护身符**: 祖传的免杀马生成脚本

---

## 🎯 经典战役

### 1. [某云平台全域突破]
```diff
+ 从外网打点到域控接管仅用4小时
! 发现并利用Nday获取SWIFT系统权限
- 触发告警次数：0 (完美隐身)
```
**战术亮点**  
`Nday攻击 → 突破边界 → 权限维持 → 票据传递 → 数据收割`

### 2. [某市政务系统「快乐闯关」记录]
```bash
#!/bin/bash
# 政务系统自助提权小助手 v1.3.37
# 警告：运行此脚本可能导致甲方系统获得"通透"特性

echo "🎮 启动快乐提权模式..."
echo "正在检测系统的安全意识薄弱程度..."

# 快乐扫描模块
function happy_scan() {
    target="http://gov-example.com/login"
    echo "🔍 发现疑似SQL游乐场，正在投放彩虹糖型Payload..."
    
    # 假装有酷炫扫描动画
    for i in {1..5}; do
        echo -n "正在绕过WAF: [${i}/5] "
        echo -ne "\033[33m"  # 黄色进度条
        printf '█%.0s' $(seq 1 $i)
        echo -e "\033[0m"
        sleep 0.5
    done
}

# 权限狂欢模块
function admin_party() {
    echo "🎉 发现弱口令彩蛋：admin/123456"
    echo "🕶️ 正在尝试兑换管理员皮肤..."
    
    # 模拟权限升级过程
    curl -s "$target" -X POST \
        -d "username=admin&password=123456" \
        -o /dev/null \
        -w "
        \033[32m[SUCCESS]\033[0m HTTP状态码: %{http_code}
        \033[33m[COOKIE]\033[0m   %{cookie_parse}"
}

# 战利品统计
echo "📊 本次快乐闯关成绩单："
happy_scan
admin_party
```

**战果展示**  
```diff
+ 💥 控制233个高权限账户（可自由切换皮肤）
+ 🎩 获得管理员VIP通行证（有效期：永久）
! ☕ 意外发现咖啡机控制接口（已实现免费续杯）
- 🛡️ 系统防御机制响应时间：超过48小时（建议升级为速效救心丸）
```

**漏洞原理**  
```python
# 伪代码解释器
def 弱口令漏洞():
    用户名 = input("请输入管理员账号：")
    密码 = input("请输入密码：")
    if 密码 == "123456":  # 魔法字符串检测
        print("🎉 特权解锁！")
        return 超级管理员权限
    else:
        print("🤖 防御系统：您可能是合法用户")
``` 

### 3. [CTF夺冠神器](https://github.com/9Insomnie/CTF-Toolkit)
[![CTF战绩](https://github-readme-stats.vercel.app/api/pin/?username=9Insomnie&repo=TokyoRain&theme=dark)](https://github.com/9Insomnie/TokyoRain)

---

## 🏆 非典型成就

```diff
+ 连续熬夜记录保持者（72小时不睡）
! 因提交太多漏洞被云厂商VIP拉黑
- 试图入侵智能咖啡机反被扣留马克杯
# 荣获甲方颁发的「最佳危机感制造奖」
```

---

## 📜 黑暗艺术证书
- **AWS黑魔法师认证** (自颁)

---

## 📡 安全通信协议
[![PGP](https://img.shields.io/badge/PGP-0xABCD1234-lightgrey)](https://keys.openpgp.org/)
[![应急响应](https://img.shields.io/badge/7x24小时响应-点击召唤-red?style=for-the-badge)](https://t.me/Insomnie7)

**暗号验证**  
在任意网站控制台输入：  
`console.log("Flag格式: flag{night_owl_"+Math.PI.toFixed(2)+"}")`

---

[![GitHub战绩](https://github-readme-stats.vercel.app/api?username=9Insomnie&show_icons=true&theme=merko&count_private=true&include_all_commits=true)](https://github.com/9Insomnie)
[![武器使用统计](https://github-readme-stats.vercel.app/api/top-langs/?username=9Insomnie&layout=compact&theme=vision-friendly-dark&hide=html,css)](https://github.com/9Insomnie)
