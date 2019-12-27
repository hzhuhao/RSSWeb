---
pageClass: routes
---

# New media

## 9To5

### 9To5 Sub-site

<RouteEn author="HenryQW" example="/9to5/mac/aapl" path="/9to5/:subsite/:category?" :paramsDesc="['Subsite name', 'Tag name inside the url of the tag page']">

Supported sub-sites：
| 9To5Mac | 9To5Google | 9To5Toys |
| --- | ------ | ---- |
| Mac | Google | Toys |

</RouteEn>

## AEON

<RouteEn author="emdoe" example="/aeon/ideas" path="/aeon/:category" :paramsDesc="['Category']">

Subscribe it by channel：
| Ideas | Essays | Videos |
| ----- | ------ | ------ |
| ideas | essays | videos |

Subscribe it by subject or topic ：
| Culture | Philosophy | Psychology | Society | Science |
| ------- | ---------- | ---------- | ------- | ------- |
| culture | philosophy | psychology | society | science |

Compared to the official one, the RSS feed generated by RSSHub not only has more fine-grained options, but eliminates pull quotes which can't be easily distinguished from other paragraphs by any RSS reader but purely disrupts the reading flow. Besides that, this feed also provides users a bio of the author in the end of the article.

</RouteEn>

## BOF

### Home

<RouteEn author="kt286" example="/bof/home" path="/bof/home" />

## cfan

### News

<RouteEn author="kt286" example="/cfan/news" path="/cfan/news"/>

## Engadget

### Chinese

<RouteEn author="JamesWDGu" example="/engadget-cn" path="/engadget-cn"/>

## iDownloadBlog

### iDownloadBlog

<RouteEn author="HenryQW" example="/iDownloadBlog" path="/iDownloadBlog/index">

Provides a better reading experience (full text articles) over the official one.

</RouteEn>

## Nautilus

### Topics

<RouteEn author="emdoe" example="/nautilus/topic/Art" path="/nautilus/topic/:tid" :paramsDesc="['topic']">

This route provides a flexible plan with full text content to subscribe specific topic(s) on the Nautilus. Please visit [nautil.us](http://nautil.us) and click `Topics` to acquire whole topic list.

</RouteEn>

## Quanta Magazine

### Archive

<RouteEn author="emdoe" example="/quantamagazine/archive" path="/quantamagazine/archive">

Compared to the official one, this feed:

1. supports LaTeX formulas, and
2. displays all pictures in the article (except those print-hidden multimedia materials).

</RouteEn>

## Simons Foundation

### Articles

<RouteEn author="emdoe" example="/simonsfoundation/articles" path="/simonsfoundation/articles"/>

### What We’re Reading

<RouteEn author="emdoe" example="/simonsfoundation/recommend" path="/simonsfoundation/recommend"/>

## Sixth Tone

### News

<RouteEn author="kt286" example="/sixthtone/news" path="/sixthtone/news"/>

## The Verge

<RouteEn author="HenryQW" example="/verge" path="/verge">

Provides a better reading experience (full text articles) over the official one.

</RouteEn>

## Vulture

<RouteEn author="loganrockmore" example="/vulture/movies" path="/vulture/:type" :paramsDesc="['The sub-site name']">

Supported sub-sites：
| TV | Movies | Comedy | Music | TV Recaps | Books | Theater | Art | Awards | Video |
| ----- | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| tv | movies | comedy | music | tvrecaps | books | theater | art | awards | video |

</RouteEn>

## World Health Organization | WHO

### Newsroom

<RouteEn author="LogicJake" example="/who/news-room/feature-stories" path="/who/news-room/:type" :paramsDesc="['类别，可在 URL 中找到']"/>