# 定义一个复数类complex重载运算符+使之能（定义一个复数类complex重载运算符）

> 更新时间：2026-09-10 (UTC+8)

您好,今天小编胡舒来为大家解答以上的问题。定义一个复数类complex重载运算符+使之能，定义一个复数类complex重载运算符相信很多小伙伴还不知道,现在让我们一起来看看吧！

1、#include using namespace std;class CComplex{ private: float real, image; public: CComplex() { } CComplex( float r, float img ) { real = r; image = img; } CComplex( CComplex another ) { real = another.real; image = another.image; } CComplex operator = (CComplex another ) { real = another.real; image = another.image; return this; } CComplex operator +( CComplexanother ) { return CComplex( real+ another.real, image + another.image ); }CComplex operator -( CComplexanother ) { return CComplex( real- another.real, image - another.image ); }CComplex operator ( CComplexanother ) { CComplex prod; //prod = this;prod.real = realanother.real - imageanother.image; prod.image = realanother.image + imageanother.real; return prod; //return CComplex( real+ another.real, image + another.image ); } CComplex operator /( CComplexanother ) { CComplex quot; float sq = another.realanother.real + another.imageanother.image; quot.real = (realanother.real + imageanother.image)/sq; quot.image = (imageanother.real - realanother.image)/sq; return quot; }};void main(){ CComplex c1( 2, 3 ), c2( 3, 3 ); CComplex c4, c5, c6, c7; c4 = c1 + c2; c5 = c1 - c2; c6 = c1c2; c7 = c1/c2;}。

本文就为大家分享到这里，希望小伙伴们会喜欢。

## 相关阅读

- [哪些因素影响了深圳试管婴儿的成功？](https://github.com/uo8lrun64a/mommy-baby-notes/blob/main/20260910jegy/jmrfvtagvp.md)
- [单身去井冈山大学附属医院能做三代试管助孕吗？附成功率费用明细!](https://github.com/sa1ec5y0bz/pregnancy-care-hub/blob/main/20260910iycg/iqtimifjyt.md)
- [宁夏比较出名的试管医院专家推荐,怎么挑选更适合](https://github.com/sa1ec5y0bz/family-health-notes/blob/main/20260910rmmb/xrmujuwwta.md)
- [延吉市试管婴儿医院哪家成功率高？延吉市做试管婴儿费用多少钱？](https://github.com/sa1ec5y0bz/pregnancy-care-hub/blob/main/20260910iycg/nqkaivwgae.md)
- [美国第三代试管婴儿全攻略：5步搞定赴美生娃无忧](https://github.com/sa1ec5y0bz/family-health-notes/blob/main/20260910wvoa/yqwqxhgosg.md)
- [2024年10月怀孕预产期时间对照，来年六月闰六月生出蛇宝](https://github.com/uo8lrun64a/parenting-daily-tips/blob/main/20260910wogy/fqymazqnni.md)
- [哈尔滨正规助孕助孕试管医院？哈尔滨正规助孕助孕试管？](https://github.com/uo8lrun64a/baby-care-journal/blob/main/20260910upmt/nsfapvhzqd.md)
- [山东试管婴儿排名前十的医院都有哪些，具体都怎样](https://github.com/sa1ec5y0bz/mommy-baby-notes/blob/main/20260910ofzz/bhbsmkvmmv.md)
- [试管婴儿应该控制多胎，高龄多种胚胎赌成功率不可取](https://github.com/sa1ec5y0bz/pregnancy-care-hub/blob/main/20260910rxwf/lrxrbfqopw.md)
- [做试管需要做宫腔镜检查能报销吗？做试管婴儿宫腔镜检查需要做吗？](https://github.com/uo8lrun64a/family-health-notes/blob/main/20260910ulcd/hurfmebkak.md)
- [认识卵巢过度刺激综合征及试管婴儿中的应对](https://github.com/sa1ec5y0bz/mommy-baby-notes/blob/main/20260910zuft/dvcxzofpqa.md)
- [301医院试管婴儿要多少钱（301医院试管医保）](https://github.com/sa1ec5y0bz/parenting-daily-tips/blob/main/20260910cxqv/guvzjgmypk.md)
- [美国第三代试管婴儿全流程手册：从签证到好孕，一站式指南](https://github.com/uo8lrun64a/family-health-notes/blob/main/20260910biha/czsgnxylqm.md)
- [如何提高卵子质量(多囊卵巢会影响卵子质量吗)](https://github.com/sa1ec5y0bz/child-care-essays/blob/main/20260910zinw/drsxaukvyx.md)

## 推荐站点

- [['https://www.chengyanghg.cn/319.html', '郑州三代正规助孕医院排名及卵子获取指南']](https://www.chengyanghg.cn/319.html)
- [['https://www.zrbbavaq.cn/22111006110670.html', '2026上海市第六人民医院供卵试管成功率解读-附费用清单 ,试管代怀中心']](https://www.zrbbavaq.cn/22111006110670.html)
- [['https://www.syldezdhkj.cn/16389420709615.html', '2026江苏供卵多少钱？附影响试管费用的5大因素参考 ,代孕哪里可以']](https://www.syldezdhkj.cn/16389420709615.html)
- [['https://www.jszgyh.com/223802368343.html', '供卵医生电话：囊胚培养失败的原因是什么？']](https://www.jszgyh.com/223802368343.html)
- [['https://www.cndcxc.com/daiyunjiage/17069.html', '试管婴儿要满足什么前提条件才可以选用冻胚移植？']](https://www.cndcxc.com/daiyunjiage/17069.html)
- [['https://www.phetpalace.com/491.html', '官方推荐：青岛正规供卵试管服务网，提供崂山本地权威咨询']](https://www.phetpalace.com/491.html)
- [['https://www.hs52.cc/sandaigongluandaihuai/145.html', '4aa囊胚相当于怀孕多久？试管移植囊胚相当于怀孕多少天？']](https://www.hs52.cc/sandaigongluandaihuai/145.html)
- [['https://www.hghbjm.com/60.html', '七个月没怀孕正常吗（同房后多久受孕）']](https://www.hghbjm.com/60.html)
- [['https://www.hg00fj88.com/2231.html', '试管供卵助-北京试管婴儿医院能一次成功吗']](https://www.hg00fj88.com/2231.html)
- [['https://www.btwtjx.cn/wuhangongluanshiguanqun/20250420/6255.html', '代孕产子公司微信,子宫肌瘤影响试管移植的成功率_子宫肌瘤影响试管移植着床']](https://www.btwtjx.cn/wuhangongluanshiguanqun/20250420/6255.html)
- [['https://www.dyqlsu.com/20250418-396.html', '如何去做试管代孕,双子宫单宫颈可以做试管吗_单子宫双宫颈可以顺产吗！']](https://www.dyqlsu.com/20250418-396.html)
- [['https://www.mimi567.com/219.html', '能做借卵试管:做试管婴儿前水果能吃吗（试管婴儿移植后吃什么水果好）']](https://www.mimi567.com/219.html)

*本文整理自母婴健康资讯，仅供科普参考。*
