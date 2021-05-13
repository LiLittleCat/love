## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/LiLittleCat/love/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LiLittleCat/love/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

<h1 id="sitetime"></h1>
<script language=javascript>
    function siteTime() {
        window.setTimeout("siteTime()", 1000);
        var seconds = 1000
        var minutes = seconds * 60
        var hours = minutes * 60
        var days = hours * 24
        var years = days * 365
        var today = new Date()
        var todayYear = today.getFullYear()
        var todayMonth = today.getMonth()
        var todayDate = today.getDate()
        var todayHour = today.getHours()
        var todayMinute = today.getMinutes()
        var todaySecond = today.getSeconds()
            /* Date.UTC() -- 返回date对象距世界标准时间(UTC)1970年1月1日午夜之间的毫秒数(时间戳) 
            year - 作为date对象的年份，为4位年份值
            month - 0-11之间的整数，做为date对象的月份
            day - 1-31之间的整数，做为date对象的天数
            hours - 0(午夜24点)-23之间的整数，做为date对象的小时数
            minutes - 0-59之间的整数，做为date对象的分钟数
            seconds - 0-59之间的整数，做为date对象的秒数
            microseconds - 0-999之间的整数，做为date对象的毫秒数 */
        var t1 = Date.UTC(2019, 8, 7, 00, 00, 00)
        var t2 = Date.UTC(todayYear, todayMonth, todayDate, todayHour, todayMinute, todaySecond)
        var diff = t2 - t1
        var diffYears = Math.floor(diff / years)
        var diffDays = Math.floor((diff / days) - diffYears * 365)
        var diffHours = Math.floor((diff - (diffYears * 365 + diffDays) * days) / hours)
        var diffMinutes = Math.floor((diff - (diffYears * 365 + diffDays) * days - diffHours * hours) / minutes)
        var diffSeconds = Math.floor((diff - (diffYears * 365 + diffDays) * days - diffHours * hours - diffMinutes * minutes) / seconds)
        /* document.getElementById("sitetime").innerHTML=" 已运行"+diffYears+" 年 "+diffDays+" 天 "+diffHours+" 小时 "+diffMinutes+" 分钟 "+diffSeconds+" 秒" */
        /*document.getElementById("sitetime").innerHTML = " 很努力地存活了 " + (diffYears * 365 + diffDays) + " 天 " + diffHours + " 小时 " + diffMinutes + " 分钟 " + diffSeconds + " 秒"
        */
        document.getElementById("sitetime").innerHTML = "💕 " + (diffYears * 365 + diffDays) + " days have we been in love."

    }
    siteTime()
</script>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<!-- 本站总访问量<span id="busuanzi_value_site_pv"></span>次
本站访客数<span id="busuanzi_value_site_uv"></span>人次
本文总阅读量<span id="busuanzi_value_page_pv"></span>次 -->
