# **Betterment**

![Robo-Advisor](https://github.com/mcody93/Homework1/blob/main/investorjunkie-robo-advisors-1.jpg?raw=true)


## ***Overview and Origin***
Betterment is a robo-advisory company. According to the [company's website](https://www.betterment.com/resources/2021-fundraising) and [Wikipedia page](https://en.wikipedia.org/wiki/Betterment_(company)), Betterment was founded in 2008 by Jon Stein and Eli Broverman and incorporated on April 7, 2009. Betterment was founded as a product of the financial crisis with an initial purpose of automatically rebalancing assets in target date funds and ultimately became the first robo-advisor as the mission evolved to support lower net worth people who typically did not have access to robust financial planning solutions with an understanding of investing and an easy to use platform with access to low cost ETFs. Investors can easily enter their personal information, risk tolerance, and financial goals and the platform generates personalized investment solutions for them. The company is currently private. According to the website and [Crunchbase](https://www.crunchbase.com/organization/betterment/company_financials), Betterment has raised $435M in 10 rounds of funding (Series A through F).

## ***Business Activities***
The most critical financial issues facing Betterment (and other robo-advisories) are low margins due to the low fee structure and the relatively high costs associated with finding new clients. Given larger banks are developing similar technologies, increases the aforementioned risks for companies like Betterment even more with the larger instituitons' immense ability to scale and access to technology.

Betterment's intended customers are everyday "Main Street" investors with an extremely wide range of capital (minimum account level is $10 and a higher end premium service is available starting at $100,000). This indicates that the potential customer base is massive. According to a February 2021 article by [Wealth Briefing](https://www.wealthbriefing.com/html/article.php?id=190292#.ZBvGvnbMJmM), the current market for robo-advisory services of $2.6 trillion worldwide is expected to reach $6.2 trillion by 2027. Further supporting the high potential for growth in the space, a study referenced in [Financial Advisor Magazine](https://www.emergingtechbrew.com/stories/2022/10/11/why-betterment-s-robo-advisor-doesn-t-use-ai) concluded that 63% of people who currently do not use robo-advisors suggested they would consider it in the next year. Although the survey was heavily tilted toward millenials, this is a clear sign that robo-advisors have a lot of potential to continue to increase their addressable market. 

Betterment's specific competitive advantages are their low account minimums ($10 as mentioned above), portfolio customizability features, and robust goal-setting features relative to peers per [Nerdwallet](https://www.nerdwallet.com/reviews/investing/advisors/betterment#:~:text=advisors%3A%20our%20methodology-,Where%20Betterment%20shines,all%20your%20cash%20is%20invested.). 

Betterment uses Flutter (an open-sourced UI software development kit) for their applications per the company's [engineering blog](https://www.betterment.com/engineering/flutter-screen-ui-testing). They also use Flutter to conduct end-to-end testing to ensure the systems are working as intended which is much easier via Flutter than some of the alternatives. The blog continues to detail how Betterment also implements a host of APIs.

Specifically, at the portfolio level, Betterment employs Monte Carlo simulations and the Black-Litterman model, an allocation model, to service their clients from a portfolio construction standpoint. According to a [Tech Brew article](https://www.emergingtechbrew.com/stories/2022/10/11/why-betterment-s-robo-advisor-doesn-t-use-ai), Betterment does not rely solely on AI and ML for portfolio construction because after testing, there were many occurrences of these advanced technologies overfitting models. However, AI and ML are still extremely important technological components of the business.

## ***Landscape***

Betterment was the first entrant in the robo-advisory space. The use of AI has been the single most important innovation in the domain. According to an April 2020 [Forbes article](https://www.forbes.com/sites/ilkerkoksal/2020/04/18/how-ai-is-expanding-the-applications-of-robo-advisory/?sh=2fc5566a55c3), AI has substantially replaced a lot of the "mundane monitoring and administrative tasks" that typically drain advisors' time. There are flags in place to alert humans if something breaches certain parameters but AI has been a huge time saver for robo-advisories. On the portfolio side, the deep learning capabilities of AI has allowed for alpha discovery via analysis of trends, investor behaviors, and historical data that traditional analysts could not easily render.

According to a [Business Review article from December 2022](https://business-review.eu/investments/the-future-of-robo-advisors-in-wealth-asset-management-234275#:~:text=Hybrid%20Is%20The%20Future&text=With%20a%20self%2Dserve%20option,way%20for%20a%20hybrid%20future.), the major trend in robo-advisories is the move to a more hybrid model of robo-advisories with the robo-advisor technology working together with dedicated professionals who make themselves available to answer specific questions and provide human support to customers. Additionally, the offerings are becoming more personalized with client-specific risk assessments and even thematic investment opportunities such as green technology. Vanguard and Betterment have already shifted to this model.

Betterment continues to respond to trends in investing. According to [Investopedia](https://www.investopedia.com/betterment-crypto-offerings-6750069#:~:text=Betterment%20now%20offers%20automated%20cryptocurrency,of%20Betterment%20cryptocurrency%20investment%20products.), Betterment began offering a cryptocurrency offering to investors in late 2022 after a period of beta testing the platform. It is imperative for Betterment and other robo-advisories to react to trends and investor wants in order to stay competitive.

Other major players in the space include large financial industry players like Vanguard Robo-Advisors and Schwab Intelligent Portfolios. However, Wealthfront, Personal Capital Advisors, Bloom, and Acorns are also smaller players in the industry right behind Betterment in terms of asset size. 

## ***Results***

Given the low margins in robo-advising, a core metric is Assets under Management (AuM). As of July 2022, Betterment ranked third in robo-advisories in terms of AuM (right behind Vanguard and Schwab) per an article in [Forbes](https://www.forbes.com/advisor/investing/best-robo-advisors/). Betterment is also highly regarded for their return profiles and platform (ranked best overall in March 2023 by [CNBC](https://www.cnbc.com/select/best-robo-advisors/)). 

According to an article by [Brookings](https://www.brookings.edu/research/robo-advice-an-effective-tool-to-reduce-inequalities/) , robo-advisors are reducing inequalities in the investment space, closing the gap between the wealthy and lower net worth investors given the fact that human advisors are monetarily incentivized to seek only wealthier clientele. Given the growth in robo-advised assets over time, it is intriguing to see robo-advisors provide access and scale to Main Street.

## ***Recommendations***

According to a February 2023 [Bankrate review](https://www.bankrate.com/investing/roboadvisor-reviews/betterment/), a major drawback to Betterment is they do not provide direct indexing (owning the actual stocks of an index as opposed to the ETF). The ability to direct index (DI) provides clients with tax loss harvesting benefits as they can pick specific stocks to sell, realize capital losses, and redeploy the capital in winners as opposed to only being able to sell the ETF which could be mixed in terms of gains/losses. In my opinion, Betterment should develop this capability in order to pose a greater competitive threat to Vanguard and Schwab. The DI capability would likely entice a large number of higher AUM clients as tax loss harvesting matters more to higher net worth individuals. As long as Betterment offers an attractive fee (as they do for other services) and maintains the excellent overall experience, DI would be a huge tailwind for them. 

According to an article by the [Financial Times](https://www.ft.com/content/075c01d3-e3e0-4f24-a189-4ade131aff16)
, providing DI would require a significant investment in resources and coders to create the DI platform if Betterment decided to create it in-house. The new models would need to understand the portfolio rebalancing and optimization schemas associated with DI as well as tax loss harvesting in order to create efficient tools for investors. Given there are less than 300 employees at Betterment, this might be better suited to be outsourced. 

Betterment should also seek to provide more service tiers. Currently, the premium (higher human touch) service is only available at the $100,000 investment level and up. According to the same Bankrate review, this is a high level relative to the industry. Betterment may want to consider lowering the minimum premium service level or, alternatively, creating more service levels (medium, for example).

In conclusion, given the immense expected growth in the robo-advisory space, movement to a preferred business model arleady developed by Betterment, the company's large existing current asset level and recognition as a fantastic tool relative to peers, I believe Betterment is well-positioned to continue to execute. Incorporating direct investing and additional service levels would further support my thesis given these features would attract more assets which is critical, especially in a low margin business. 

## ***Works Cited***
[Bankrate: "Betterment review 2023"](https://www.bankrate.com/investing/roboadvisor-reviews/betterment/)

[Betterment Company Website (Sources of Funding)](https://www.betterment.com/resources/2021-fundraising)

[Betterment Engineering Blog: Flutter](https://www.betterment.com/engineering/flutter-screen-ui-testing)

[Betterment Wiki](https://en.wikipedia.org/wiki/Betterment_(company)) 

[Brookings: Robo-advice: An effective tool to reduce inequalities?](https://www.brookings.edu/research/robo-advice-an-effective-tool-to-reduce-inequalities/) 

[Business Review Article: "The Future of Robo-Advisors In Wealth & Asset Management"](https://business-review.eu/investments/the-future-of-robo-advisors-in-wealth-asset-management-234275#:~:text=Hybrid%20Is%20The%20Future&text=With%20a%20self%2Dserve%20option,way%20for%20a%20hybrid%20future.)

[Charles Schwab Press Release: Directing Indexing](https://pressroom.aboutschwab.com/press-releases/press-release/2022/Schwab-Launches-Schwab-Personalized-Indexing/default.aspx)

[CNBC: "Robo-advisor dream of disrupting Wall Street wealth is not working out exactly as planned"](https://www.cnbc.com/2022/01/27/roboadvisor-disruption-of-wall-street-wealth-is-not-working-out.html)

[CNBC: "The 5 best robo-advisors when you want to be hands off with your investments"](https://www.cnbc.com/select/best-robo-advisors/)

[Crunchbase Additional Funding Information](https://www.crunchbase.com/organization/betterment/company_financials)

[Emerging Tech Brew: "Why Betterment’s robo-advisor doesn’t use AI"](https://www.emergingtechbrew.com/stories/2022/10/11/why-betterment-s-robo-advisor-doesn-t-use-ai)

[Financial Advisor Magazine: "Only 1% Of Investors Use Robo-Advisors, Survey Says"](https://www.emergingtechbrew.com/stories/2022/10/11/why-betterment-s-robo-advisor-doesn-t-use-ai)

[Financial Times: "Technology providers push direct indexing into the mainstream"](https://www.ft.com/content/075c01d3-e3e0-4f24-a189-4ade131aff16)

[Forbes: "5 Best Robo-Advisors Of March 2023"](https://www.forbes.com/advisor/investing/best-robo-advisors/)

[Forbes: "How AI Is Expanding The Applications Of Robo Advisory"](https://www.forbes.com/sites/ilkerkoksal/2020/04/18/how-ai-is-expanding-the-applications-of-robo-advisory/?sh=2fc5566a55c3)

[Forbes: "Top-10 Robo-Advisors By Assets Under Management"](https://www.forbes.com/advisor/investing/top-robo-advisors-by-aum/)

[Investopedia: "Betterment Launches Crypto Offering With Four-Themed Portfolios"](https://www.investopedia.com/betterment-crypto-offerings-6750069#:~:text=Betterment%20now%20offers%20automated%20cryptocurrency,of%20Betterment%20cryptocurrency%20investment%20products.)

[Investopedia: "Robo-Advisor"](https://www.investopedia.com/terms/r/roboadvisor-roboadviser.asp)

[Investopedia: "Understanding Robo-Advisors"](https://www.investopedia.com/terms/r/roboadvisor-roboadviser.asp#:~:text=The%20first%20robo%2Dadvisor%2C%20Betterment,through%20a%20simple%20online%20interface.)

[Medium Opinion Article about Betterment](https://medium.com/@ossowski.chris/is-betterment-ready-for-ipo-or-spac-46d1bc33fd07)

[Nerdwallet: "Betterment Review 2023: Pros, Cons and How It Compares"](https://www.nerdwallet.com/reviews/investing/advisors/betterment#:~:text=advisors%3A%20our%20methodology-,Where%20Betterment%20shines,all%20your%20cash%20is%20invested.)

[Tech Brew:Why Betterment’s robo-advisor doesn’t use AI](https://www.emergingtechbrew.com/stories/2022/10/11/why-betterment-s-robo-advisor-doesn-t-use-ai)

[Wealth Briefing: "Global Robo-Advisor Market To Reach $6.2 Trillion In 2027"](https://www.wealthbriefing.com/html/article.php?id=190292#.ZBvGvnbMJmM)

[Wikipedia: "Betterment"](https://en.wikipedia.org/wiki/Betterment_(company))

