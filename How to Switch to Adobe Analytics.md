# How to switch to Adobe Analytics

Congratulations on the decision to switch to Adobe Analytics! You’ve taken your first step into a larger world. Although no two analytics tools are exactly the same, the leading web analytics tools (Adobe Analytics and Google Analytics) share enough common functionality that you can quickly learn how to get meaningful insights into your business.

This guide presents common report types that help you to learn core concepts and workflows in Adobe Analytics, focusing on key similarities and differences between Adobe and other popular tools. This guide is designed for analysts who are familiar with basic digital analytics concepts, but new to Adobe Analytics.

In this guide, you will learn:

1. Core Adobe Analytics concepts and capabilities and how they relate to other analytics platforms
1. How to translate specific workflows and terminology into Adobe Analytics
1. A few advanced capabilities unique to Adobe Analytics

Additionally, this guide provides step-by-step instructions for working with features in the following report types:

*Site Content Reports
*Marketing Channels Reports
*Products and Funnel Reports


## Requirements

You can read and learn from this guide with no special requirements. However, to perform  steps shown in this guide yourself, you will need the following:

1. Access to an existing Adobe Analytics account, or a demo account
1. A basic understanding of web analytics concepts, such as page views, bounce rates, conversions, and funnels
1. Access to an instance of Analysis Workspace with sufficient privileges to create and share segments and calculated metrics
1. Administrator or developer help, in some cases, to fully implement your Adobe Analytics account.

## Get started in Adobe Analytics

To get started in Adobe Analytics:

Make sure that your Analytics is fully implemented with web properties.

1. [Log in to Adobe Experience Cloud](https://marketing.adobe.com/resources/help/en_US/analytics/getting-started/analytics-navigation.html).
  
1. [Navigate to Adobe Analytics](https://marketing.adobe.com/resources/help/en_US/analytics/getting-started/analytics-navigation.html) and Analysis Workspace.

## Analytics visual tools

Adobe Analytics provides two different visual tools to analyze your business: Analysis Workspace and Reports and Analytics. In Analysis Workspace, you work with visualizations that correspond to reports in different tools. These visualizations show key metrics for your web business. The visualizations are not only more flexible and robust in displaying metrics, they are also easier to create. They also provide much more detail than traditional reports. You create visualizations by dragging and dropping data tables,dimensions, metrics, segments and time periods on the Analysis Workspace user interface. You can also extend visualizations with right-click options. For more information on the features of Analysis Workspace visualizations, see the [Analysis Workspace Overview](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/). Adobe's Reports and Analytics capabilities also correspond with report types in other tools. Both tools offer unique capabilities that go beyond simply measuring page traffic so that you can better understand how pages convert users. 

## Comparing report types

This is a high-level section that Russ mentioned he might author.


## All Pages Report

You can construct either a report or a visualization in Analytics that is similar to an **All Pages Report** in other tools. This report provides content performanc--one of the fundamentals of web analytics. This section describes the following:

1. How to construct an **Pages** Report with the Analytics report interface.
1. How to construct a **Page Performance** visualization in Analysis Workspace similar to an All Pages Report.

Additionally, by creating these in Analytics, you learn:

1. How to navigate the reporting interface to measure page traffic
1. Key Adobe Analytics concepts, such as report suites, dimensions and metrics
1. How to quickly customize reports
1. How the content on your pages contributes to conversion
1. How to share your report with others

## Construct a Pages report

To construct this report: 

1. In Adobe Analytics, click the **Reports** tab and then click **View All Reports**. Note the menu showing all the reports set up in your account. These menus, and the reports within them, are your reports suite and are customized to your specific Adobe Analytics implementation.

**Reports Tab Image Here**

2. Click **Content** > **Pages**. The **Pages** report appears and shows [dimensions] (https://marketing.adobe.com/resources/help/en_US/reference/dimensions.html), [metrics] (https://marketing.adobe.com/resources/help/en_US/sc/implement/ref-metrics.html), and page names.

**Pages Report Image Here**

## Create a visualization for Pages

Analysis Workspace provides an easier way to see all types of available dimensions and metrics. It functions similar to creating basic repors but greatly enhances the speed, flexibility, and customizability of visualizing and analyzing your data. 

In Analysis Workspace, the **Page Performance** visualization shows traffic metrics for the **Page** dimension.

To create a **Page Performance** visualization in Analysis Workspace:

1. Click **Workspace** at the top left of the Analytics screen.
1. Click the blue **Create New Project** button. 
1. For your project, you can use a Template Project or a Blank Project. A blank project is a blank canvas you use to build your visualization. A template is a set of pre-configured reports, components, and visualizations. [Templates are helpful starting points] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html) for building larger dashboards or analyses, and to help others see your insights more quickly. If your organization has an existing template, you can click that and explore the details that follow. Otherwise, click select the **Content Consumption-Web** template and then click **Create**. 

**Template selection image here**

4. Scroll down to find the **Top Pages** section on the **Content Consumption** screen. Your template includes visualization starting points, including this one for page content. The information in the visualizations is for demonstration purposes only and does not reflect any real data. Although many **Content** screens [often show dashboards] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/) at the top that summarize numerous metrics, this template first shows a flow visualization at the top. This screen can be customized to present visualizations in any order.

**Top Pages Visualization Image Here**

***About Report Suites***

For this template, the fictitious data is based on the report suite showing in the **Report Suite Selector**. Click on the selector to choose a different report suite or continue with the `Cross-Industry Matisoft Data` report suite that appears with the template. None of the report suites associated with the templates have real data.

**Report Suite Selector image here**

In Adobe Analytics, a report suite is the repository where you send your data and from which you pull reports. Usually, a report suite collects data from one website. This is similar to a **View** or a **Profile** in other analytics tools.

Your organization may have different report suites set up for different sites and apps. Check with your administrator to understand where you should be pulling reports from.

One key difference between Adobe's data collection method and many other tools is that you specify which report suite(s) to send data to when you send the data. This is different from other popular tools that typically send all your data to one collection location and then filter that down to create different views or profiles via the admin interface. You cannot shift data between report suites.

You can also build [virtual] (https://marketing.adobe.com/resources/help/en_US/reference/virtual-report-suites.html) report suites, which let you build filtered views from a normal report suite.

For more information on report suites, see the [Report Suites Manager] (https://marketing.adobe.com/resources/help/en_US/reference/report_suites_admin.html) help.

## Working with Workspace toolbars

Analysis Workspace includes three toolbars that appear according to the icon you select on the far left of the screen.*

**Toolbar icons image here**

*Panels toolbar: Shows options for creating the panels that hold your visualizations
*Visualizations toolbar: Shows options for structuring or customizing your visualizations according to form
*Components toolbar: Shows options for adding components to visualizations

## Customize your visualizations

The following section describes ways to customize your screen and visualizations. The typical screen actions associated with customizing your visualizations include dragging and dropping screen elements and right-clicking visualization items to select other options and actions. 

1. To customize the name of this project, click the title in the uppper left of the screen and type the new name.

1. To change the settings of your project, or to save, share, and edit it, click the applicable menu beneath the title and select the applicable option. Each menu item includes [keyboard shortcuts] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/fa_shortcut_keys.html) as well.

**Project Title and menus image here**

3. On the left side of the screen, note the **Component** toolbar, which contains groupings for **Dimensions**, **Metrics**, **Segments**, and **Time**. These components are all available to use in your visualizations. The **Dimensions** grouping is expandable into sub-components. Under **Dimensions**, click the **Page** arrow **>** that appears when you hover over it. The **Page Items** then appear as sub-components.

**Page arrow image here**

5. Select the date range for your visualization. Click the Date Range in the upper right of the screen to open the Date Picker. The range you select here applies to the entire panel in this Analysis Workspace project. This template defaults to the last month across all panels.

**Date Picker image here**

***About Panels***

A Panel is a collection of visualizations. You might have many visualizations that you want to group in different categories, but also keep in the same project. To do this, you can create multiple panels that  hold the visualizations that you move to them. For example, the Content Consumption template contains only one panel--called Content Consumption.

**Content Consumption panel image here**

If you click the drop down arrow on the panel, it collapses to show other panels you have created (in this case, none). If you click the arrow again, it expands the panel to fully display on the screen. To add more panels, click **Insert** > **New Blank Panel** and choose the type of panel you want to add. For more information on panels, see the [Panels] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/panels.html) help.*

## Understanding Content Reports

This section describes elements in the page performance visualization (entitled **Top Pages** in this template). Refer to the following image to understand the details of the report.

**Pages report image here**

This type of visualization is called a [Freeform Table] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/freeform-table.html). You can easily build or modify these tables by dragging and dropping elements on to them. This table shows traffic metrics for the **Pages** dimension, including the following:

*[Page Views] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_page_view.html)
*[Visits] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_visit.html)
*[Time Spent per Visit] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_time_spent.html)
*[Entries] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_entries.html)
*[Bounce Rate] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_bounce_rate.html)
*[Exit Rate] (https://marketing.adobe.com/resources/help/en_US/reference/metrics_exits.html)

For more metrics descriptions, see the [Metrics] (https://marketing.adobe.com/resources/help/en_US/reference/metrics.html) help topic.

***About Bounce Rate***

Bounce Rate is a common KPI that is used to help measure the effectiveness and the relevance of landing pages in most analytics tools. This is commonly defined as visits that enter the website but do not include a click to another page. For Adobe Analytics, this metric does not include visits that include a click on the landing page. Interactions like downloads, video plays, and navigation may cause the bounce rate to be different from other tools.

To compare like metrics across tools, use the **Single Page Visits** metric in Adobe Analytics instead of Bounces. The **Single Page Visits** metric includes the total number of visits that only included one page view, or visits that enter the website but do not include a click to another page.

## Create a Calculated Metric

Most out-of-the box metrics in Adobe Analytics provide counts of things: how many pages viewed, how many files downloaded, how many seconds visitors spend on the site. Other tools, Google Analytics in particular, often show *index metrics* or *calculated metrics* by default.

Index metrics typically divide counts of one thing by counts of another thing: for example, you might divide Conversions by Visits to get Conversion Rate. These metrics are helpful when you are trying to compare the effectiveness of items with different volumes. For excample, organic search might bring in ten times the traffic of social media, but conversion rates might show that social media converts at a far higher rate than organic search.

Other tools let you create basic calculated metrics that divide, multiply, add, and subtract. Adobe's calculated metrics builder goes beyond this by letting you add segments an include mathematical functions like mean, standard deviation and variance.

If you do not already have a calculated metric in your project, you can create one by following these steps:

1. On the **Components** toolbar, Click the **+** next to the **Metrics** component box.
1. Add the following title: **Page Views per Visit**.
1. For **Format**, select **Decimal**.
1. Increase the **Decimal Places** to 2. 
1. Drag the Page Views metric to the Definition box. Then drage the Visits/Vistors metric to the same box under the first metric (wait until the blue line appears to drop it).
1. Between the two metrics listed in the Definition, select the Divide operator (if not already selected).
1. Click **Save**. Note that the new calculated metric is added to the **Metrics** box. Anytime you make a change to the metric definition.

## Add metrics to visualizations

To add your new calculated metric to the page performance visualization (or **Top Pages** free-form table):

1. Expand the **Content Consumption** panel, if not already expanded. 
1. Drag your new calculated metric from the Metrics box to the page performance freeform table header. The blue flag that appears as you drag the metric indicates where the column is added when you drop it. The visualization now includes a new column with new metric data.

## Page value: add conversion metrics

Conversion metrics show data about success events, such as purchases, downloads, or any other action that you want users to take on your website.
To add conversion metrics to the page performance visualization (or **Top Pages** free-form table) you can refer to the following example procedure:

1. In the **Components** search box, type `Online Revenue`.
2. Drag and add it next to the metrics on the page performance table.
3. Sort the pages in descending order, based on how much online revenue they generated. To do this, hover between the trend line and the online revenue totals at the top of the column. When the downward arrow appears, click it. To sort it back in ascending order, click the upward arrow that appears when you hover in the same place.

Note that the online revenue is attributed to the order confirmation page. This is because the pages report uses a *Last Touch attribution* model. 

## Page value: add participation metrics

[Participation] (https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/participation_metric.html) is a unique type of attribution available for all metrics in Adobe Analytics. Participation models assign full credit for conversions to all dimension values that a user touched prior to the conversion. For instance, if a user spends $100 on your site and hits 10 pages during the visit, Revenue Participation gives $100 credit to each of those 10 pages. You can set the look-back window to be during the same visit, or for the same visitor during the reporting date range. This not only useful, but critical when trying to accurately understand how different pages, campaigns, search terms, etc. contribute to ultimate conversion.

Because full credit is assigned to each dimensional value the visitor hits along the way, it is not possible to provide a sum for participation metrics to understand the total number of conversions. Such a count would be too high to be useful. Instead, you can use the value in the column header, which deduplicates the data. Participation metrics are retroactive, applying past data to the new metric.

Your administrator can also set up calculated participation metrics for your organization.

To add a participation metric:

1. Create a new metric in the Calculated Metric Builder, as performed previously.
1. Drag the success event **Orders** into the **Definition** box.
1. Change the attribution model of that event to `Participation` under the Settings gear. Choose **Visit** lookback. 
1. Save the metric.
1. Drag the calculated metric to the pages report.

You can also create participation that mimics the Total Page Value, as found in other tools, except that you can put participation in any report you want, for any conversion metric you track. For example, you can use Calculated Metrics to divide `Online Revenue (Participation)` by `Visits`. Similarly, you can also divide `Online Orders (Participation)` by `Visits` to understand the page conversion rate. Unlike the metric in other tools, which is bounded to Page Value report, you can use thisfor *any metric in Adobe Analytics.*

## Content Velocity

Content Velocity is a pre-set calculated metric in Analysis Workspace. This metric determines how many page views each page generates. It is calculated by dividing Page Views (Participation) by Page Views. This can be a great way of determining which content is most likely to generate engagement with additional content. 

## Marketing Channel Reports

In Analysis Workspace, the Marketing Channel report shows how users found your website. This includes both tagged (Paid Search, Email) and untagged (Natural Search, Organic Social Referrers) traffic. If you want a pie-chart of traffic, of online orders, or of online revenue, the marketing channel report is best.  
  
The **Components** menu includes a Last Touch Channel and a First Touch Channel report. Last Touch Channel is the same thing as Marketing Channel, *in Workspace*. First Touch Channel is the Acquisition Channel. 

The **Components** menu includes a Last Touch Channel and a First Touch Channel report. Last Touch Channel is the same thing as Marketing Channel, *in Workspace*. First Touch Channel is the Acquisition Channel. 

This section includes the following topics:

1. How Adobe measures traffic source contribution to traffic and conversion; how this methodology differs from other tools; and how it can be customized
2. How to build and easily customize reports that show campaign contributions to traffic and conversion
3. How Adobe Analytics' built-in capabilities enhance and extend media data

Compared to other tools, Adobe Analytics provides more flexibility on how to measure campaigns and traffic channels. This section explains core concepts related to marketing channel measurement and shows features that Adobe provides for this. It also shows how Adobe’s Calculated Metric capabilities can improve speed to insight compared with other platforms. It also includes a brief overview of some advanced features you may want to explore further.

**Campaign Tracking in Adobe Analytics**

Other analytics tools have strict guidelines on how to tag campaign URLs. You must use specific URL parameters, such as utm_campaign, WT.mc_id, cm_mmc, etc. With Adobe Analytics, you have control over which parameter(s) is used to identify campaigns. For example, you can set Adobe up to look for whatever you were using with your old platform, so you do not need to re-tag your URLs. You can also set things up to look first for a new parameter, like cid=, but then return to whatever you used previously. This helps if you want to simplify tagging requirements but also want to make sure old campaigns still floating around get tracked.

In Analysis Workspace, the Marketing Channel report shows how users found your website. This includes both tagged (Paid Search, Email) and untagged (Natural Search, Organic Social Referrers) traffic. If you want a pie-chart of traffic, of online orders, or of online revenue, the marketing channel report is best.  
  
**Traffic Source Attribution in Adobe Analytics**

Adobe includes many reports for traffic source attribution. For best results, organizations should implement them intelligently and curate them conscientiously. It also helps to enable the Marketing Channels reports and then hide other traffic source reports that might work at cross purposes. Perhaps this might include hiding referring domains or search engines.

When setting up your Marketing Channels, review the [default list of social networks:] (https://helpx.adobe.com/analytics/kb/list-social-networks.html).

On the Marketing Channels Report, find the Marketing Channel Instances metric.

**Marketing Channel Instance image here**

Instances tells us the total number of times that a user clicked to your website and the Marketing Channel changed. Similar to other analytic tools, the Marketing Channel persists beyond the initial click-through until the user clicks through from another campaign or referring domain. *Visits* here means the total number of visits where the most recent Marketing Channel was, such as Email. Therefore, “Marketing Channel Instances” here gives the total number of clicks from Email.  
  
Adobe also gives you more flexibility about your attribution window than most other tools. The windows aren't channel-specific, but the lookback window is up to you. No six-month attribution window limit exists, as in other analytics tools. You will see a larger percentage of Direct users in Adobe than in others, but this is easily managed with tagged campaigns.

## Analyze Campaign Performance with Marketing Channels

It is important to understand not just the total number of Paid Search visits and conversions, but also which campaigns drove those conversions. To dive deeper into an individual channel performance, use the Marketing Channel Detail report. This is generally the only report that has the same attribution model as Marketing Channels.
  
There may be additional reports in your implementation based on Marketing Channel detail – check with your administrator are available and best to use.  
  
The Marketing Channel Detail report shows you a second-level of granularity for each Marketing Channel. This is customized to each Channel, in each Adobe Analytics implementation. Typically, this is set to show the campaign tracking code for all tagged marketing channels, the referrer for all channels based on referrers (such as Organic Social or Organic Search), and the entry page name when neither of these exist (such as Direct or Mobile App). This is also worth verifying with your Analytics administrator. 

**Add Marketing Channel Detail as a Secondary Dimension**

To add this, in **Component** search, type `Marketing Channel Detail`. Drag and drop this component on top of **Email**.

You can add breakdowns to multiple primary dimensions in this report, and in the same way that you added a breakdown to the primary dimension, you can also break down secondary dimensions (and tertiary dimensions, and beyond). This is called “infinite breakdowns” in Adobe Analytics and it’s a great way to dive really deep into your data.

**Analyze Total Channel Contribution to Conversions**

Previously, the Participation attribution model on the **Pages** report helped us to understand the average value of specific content. Similarly, we can attribute all Online Revenue to every page that a user interacted with during a visit prior to converting. This can be used on any dimension, to attribute all Online Revenue to every dimension value that a user touches during their visit. This is the *Visit Participation* model works.

Similarly, *Report Participation* allows you to attribute revenue back to all dimension values that a user touched prior to conversion *across the whole report date range*. Report Participation is an *Any Touch* attribution model.

**Add Online Orders (Report Participation) to the Last Touch Channel report**

1. Find the **Online Orders (Report Participation)** metric.

2. Add it to the Marketing Channels Report.

**image here**

You can read this report as: *Each click (instances) represents this amount from Print ads. Print ads were the last-touch channel for 416 total Online Orders, but participated in 5.3K total Online Orders (13% of site total).*

Remember, as with the Visit Participation metric, these values cannot be summed. The same order in Participation models is attributed to multiple Marketing Channels.

## Analyze how channels assist conversions

If you want to see the total number of Online Orders that each channel participated in but was not the last touch--sometimes referred to as *assists*, you can use Adobe's Attribution IQ. This feature allows for advanced attribution modeling. To use this feature:

1. Open the Calculated Metric Builder.
1. Name the metric `Online Order Assists (Report Participation)`.
1. Drag **Online Orders** into the definition.
1. Hover over the right side of the metric in the definition, then click on the gear icon.
1. Click **Use non-default attribution model**.
1. Set the **Model** to **Participation**.
1. Select **Visitor (Reporting Window)** as the Lookback Window.
1. Click **Apply**. Your metric definition should look like this:

  **image here**

9. Find **Online Orders** in the toolbar and add it underneath the **Online Orders (Participation|Visitor)** component.
10. Click to change the operator from Divide to Subtract.
11. Save the calculated metric and add it to the Marketing Channels Report.

**image here**

This shows all online orders that each channel participated in but was not the last-touch channel. 

If you sum up **Online Orders** with **Online Order Assists**, it should equal **Online Orders (Report Participation).**

In other analytics tools, you can only do this for *eCommerce + Goals for Channels & Campaigns*. In Adobe Analytics, you can do this for *all* dimension values and for *all* events.

## Attribution IQ

Adobe's Attribution IQ feature allows you to apply custom attribution models to any of your reports. This is unique only to Adobe Analytics. You can use this to understand how different marketing efforts initiate, assist, and close deals for you. Additionally, it can provide insights on linear allocation, J-Curves, time decay, and attribution models within attribution models. To read more on this feature, see [Attribution IQ help] (https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/attribution.html).


## Integrate Media Data

Something that Google Analytics likes to brag about is their integration with Google Ads, which allows you to pull impression, click, cost, and view-through information into Google Analytics. Which, we agree, is clutch. But it only works with Google. Because, as we all know, Google equals the internet.

Adobe has a number of ways to integrate your media data into Analytics too. First, of course, is the integration with Adobe Media Optimizer and Adobe Ad Cloud. This integration is pretty much automatic. Ditto Adobe Campaign for email.

There is also a Data Connector for DoubleClick which allows you to pull in DoubleClick data, including view-through conversions. Additionally, many third-party email platforms have Data Connectors of their own.

Finally, a relatively new feature called Advertising Analytics lets you pull impression, click, and cost data from Google, Bing, and Yahoo! into Adobe Analytics. We’ve included links to all of these within the forum post.

# Lesson 3: Products and Funnel Reports

## Objectives

1. Get hands-on with new ways to build ad hoc product and conversion funnel reports
2. Learn how to pass visitor data into other Adobe solutions for retargeting
3. Hear about options to include offline data in Adobe Analytics

## Lesson Context

If you’re used to Google Analytics (especially the free version), you are probably also used to having to find painful and time-intensive work-arounds to report on your sales funnels *exactly* how they should be measured. Good news: those days are all behind you. Adobe Analytics bakes in advanced analysis functionality that allows eCommerce & content sites alike to define unlimited and fully customizable product and funnel reports.

This lesson will teach analysts how to use Adobe Analytics to measure product performance, with a focus on measuring a standard eCommerce checkout funnel. While we will talk through the standard eCommerce metrics, we will also call out how this reporting can be customized to measure other types of funnels like registration flows.

Adobe Analytics allows you to do more than just *report* on data. Easily take action on your data by passing segments of users to tools like Adobe Campaign or Adobe Target. This lesson will discuss how to create these segments and how to share them with other Adobe solutions.

## Exercise 3.1: Analyze Product Performance for Desktop Visitors

The next panel in our custom template looks at product performance. For those of you that don't run an eCommerce site, most of these concepts will still be valuable to you—please stay for just a short while longer!

### Find the Products Performance Report in the Summit Lab Template

Fancy. If you’re used to products reporting in other analytics tools, this should look familiar. The concepts are about the same. But there’s something else on this report that might be throwing you off: “Unspecified” is showing up as a dimension line item.

> **What in tarnation is "Unspecified?"**<br><br>
> On many reports you may see a row labeled "Unspecified", or "None". Most of the time, this can safely be ignored.<br><br>
> Adobe likes to give you all data for every metric on your report, even if there's no associated dimension value for it. They do this to provide context to your data. That's what they say, anyway.<br><br>
> So if we're looking at a Products report and have a metric like, sigh, Occurrences on it, there are plenty of things that happened on the site that didn't involve a product. So those Occurrences show up with "Unspecified" for the dimension.<br><br>
> Now, if your products report shows "Unspecified" getting credit for, say, product views or cart additions, that may be an implementation issue. Use your gut to decide if it looks fishy.

![30](./images/image30.png)

1. Find the “Desktop Visitors” segment in the left rail.

    > **What's a Segment?**<br><br>
    > A segment lets you filter a report by something that's not on that report. For instance, you could apply a segment to a Products report to show only mobile device activity, even though nothing on the Products report tells you about device type.<br><br>
    > Similar to the calculated metrics engine, Adobe's segmentation engine is head-spinningly advanced compared to what other tools can do. We don't have time to dig too deeply into it today, but we strongly recommend taking the time to learn more about it!

2. Preview the segment definition by clicking the info icon in the component.

3. When you hover over the component, you’ll see an “i” icon appear in the right corner. Clicking this icon will open a preview of the segment definition, including a graph of how many visits, visitors, and page views are included in this segment.

    The Desktop Visitors segment uses the criteria “Mobile Device Type = Other”. Mobile Device Type? Other? There are legacy reasons for these labels – just remember that “Mobile Device Type” is the dimension to use for measuring desktop vs mobile performance, and that “Other” represents Desktop visits.

    ![31](./images/image31.png)

### Drag and drop “Desktop Visits” to the top of the panel

You’ll see at the top left side of the panel that there is already a segment applied to this report, to filter data for just website (excluding mobile app) visits. *When you apply two segments to a report, Adobe Analytics shows only data that matches both criteria*.

![32](./images/image32.png)

When you’re done, you’ll get a report that looks like this: easy-peasy, a product performance report filtered for Desktop visitors only.

![33](./images/image33.png)

As expert web analysts, we hope that your first instinct when viewing this report is to use index metrics and/or start to look at the conversion funnel fallout. For the sake of having fun, let’s take a step back and look at the overall site-wide conversion funnel using a “fallout report.”

## Exercise 3.2: Analyze Conversion Fallout from Category Pages

A Fallout Report in Adobe Analytics is a dynamic visualization showing how many visits or visitors complete specific actions in sequence. The classic example is an eCommerce conversion funnel – how many people view products, add items to their cart, begin checkout, and purchase. But fallout reports can also show how people go through sequences of pages or page types, or how visitors engage with different campaigns & channels.

To stay consistent, we’ll continue to look at the eCommerce Conversion Funnel.

### Scroll to find the Product Conversion Funnel Report

When you’ve scrolled down to find the Product Conversion Funnel report, you might try to compare the data here against the Products Performance Report. When you do that, you might notice that they don’t match at all. There’s a reason for that.

![34](./images/image34.png)

The Product Performance Report shows the total number of Product Views, Cart Additions, and Online Orders. By contrast, the fallout visualization shows the total number of *visitors* who viewed products, the total number of *visitors* who added items to their cart after viewing products, and the total number of visitors who bought products online after having viewed products and adding items to their cart.  
  
In short: the fallout visualization enforces sequence and deduplicates. The freeform table does neither. Wield your power carefully!

Fallout reports are also great because you aren’t limited to using either metrics or dimensions in your step definitions – you can use *both* together. See – you *can* have it both ways! Let’s take a closer look at the fallout from Product Category (Product Browse Grid) pages.

### Find the Page Type Dimension in the Left Rail

### Click into the Page Type dimension

1. Once you’ve found Page Type in the left rail, don’t drag and drop quite yet – hover over the dimension and click into the right-facing arrow that appears.

2. This is going to open a menu of the most common Page Type values in the last six months. You can use these dimension values the same way that you can use Segments, Dimensions, and Metrics in the report. My, that’s convenient.

    ![35](./images/image35.png)

3. Find “Category”, then drag and drop this on top of the “Product Views exist” step.  
  
    ![36](./images/image36.png)

4. Stellar. If all has gone well, your report will look like this:

    ![37](./images/image37.png)

Now, you’re going to see all visitors who go to Category pages, and the product fallout from those pages. Fantastic! Let’s customize this bad-boy even further.

### Change Container from Visitor to Visit Scope

Remember when we said that by default, this is going to show you the path of Unique Visitors and include All Visits as the first touchpoint? We can change that.  
  
1. In the upper right-hand corner of the Fallout report, there is a gear icon. Click it to open the Fallout Settings.

2. Toggling the container from Visitor to Visit will show the total number of *visits* that go through your sequence during a single visit, instead of the total number of *visitors* who go through your sequence during the report timeframe. For Category Page Fallout, let’s change this to be **Visit** scoped.

### Start Funnel at Category Visits

In the same settings menu, there is an option to un-check a box for “Show ‘All Visits’ as the first touchpoint.” This removes the bar at the very start of the funnel that shows you the total number of Visits/Visitors, making the first step of your sequence Category Page Visits.  
  
![38](./images/image38.png)

You can read this report like: of the 35K visits to the category pages, 86% view products and 33% ultimately place an order within the visit. Wow that’s an effective website. Let’s move on.

![39](./images/image39.png)

## Exercise 3.3: Cart Abandonment Segments

The Adobe Experience Cloud makes it dead simple to turn segments in Analytics into Audiences in other Adobe Marketing Cloud solutions, where you can craft personalized and relevant experiences based on user’s web behavior. Let’s create a segment of visitors who have added products to their cart but not placed an order, and send it to the Experience Cloud.

### Open the Segment Builder

1. From the left rail, scroll down to the “Segments” and click the plus icon to create a new segment. Did we mention there’s a keyboard shortcut for that? There is! Hats off to you if you commit this to memory and actually use it.

### Name the Segment & Add Criteria for Visits that Abandon a Cart

1. Name your segment “Cart Abandonment Visits,” or something along those lines.

2. Do a search for “Abandon Cart” in the left rail. Adobe has included an “Abandon Cart” segment template for you to use as a starting off point – templates like this are identified by the folder-with-magnifying-glass icons. Lucky for us, this template is exactly what we need with no customization required: visits that added an item to their cart and then did not place an order.

3. Drag and drop the blue component into the segment definition. It will look like this:

    ![40](./images/image40.png)

### Save the Segment and Share to Experience Cloud

OK – Buckle up and prepare to send this to the Experience Cloud.

1. Underneath the segment definition, there’s a check-box. Check the box. Adobe will suggest a look-back window for you; let’s keep 90 days for these purposes.

    ![41](./images/image41.png)

2. Click save. And with that, you’ll feel the ground moving under your feet – you’ve just shared an audience across Adobe Experience Cloud solutions. Now you can use this to trigger emails in Campaign, show banner ads via Ad Cloud, or trigger a personalized offer the next time the visitor comes to your site via Target.

We don't want to make your head spin too much more on this Thursday morning. But in passing we do want to highlight a couple of relevant features in Adobe that may come in handy for conversion funnel and products analysis: Virtual Report Suites, Data Sources, and Classifications.

## Next Steps

### Exclude Fraud Using Virtual Report Suites

A Virtual Report Suite is a view that's built from a normal report suite's data, with one or more segments permanently applied. One really nice thing about them is that they are fully retroactive—you can update the segment and filter out stuff that already happened.

Two ways we often use a VRS are to eliminate bot traffic that you didn't catch before the fact, and to throw out online orders that were either fraudulent or had a currency conversion issue (Indonesian Rupiah, I'm looking at you).

> **PRO TIP:** If you're just implementing Adobe Analytics now, consider setting up a VRS from the get-go and using it all the time, even if initially you're not filtering anything out. Then, if issues do arise over time, you can add a segment to that VRS and you won't have to retrain stakeholders on switching report suites or finding segments/calculated metrics in a different suite.

### Integrate Offline Data using Data Import

Another underappreciated feature of Adobe Analytics is the Data Source import. This lets you push offline data such as cancelled orders and lead-to-revenue info back to Adobe.

> **PRO TIP:** To get the most out of this feature, make sure to capture an online transaction ID at the time of the online conversion. Then, you can batch upload offline data referencing that same transaction ID and the new data will associate with the online activity related to that transaction. It's vaguely magical.

### Roll Up/Clean Up Dimension Data using Classifications

While we're looking at product data, this is a good time to talk about *classifications*. You're old enough. This is a way to import lookup tables of meta data (that means "data about your data") to a dimension in Adobe Analytics.

Products are a classic example of where this is useful. Let's say my site tracks products by their SKU. I see SKU 04852291147 is selling like hotcakes. Great. But I don't know what product that is.

Classifications let me upload a table translating that SKU into a product name, department, brand, price point, what have you. Now I can pull a product name report, or brand report.

This is a powerful and often underutilized feature of Adobe Analytics. Don't be intimidated—check it out. Anybody who has ever used a pivot table can grasp the concept in about 30 seconds.

This is where we highly recommend speaking with your Analytics administrator to understand exactly what you have available to you, since this will be highly customized to your business.

# Closing: Congratulations!

You did it! By this point, you should have a good understanding of how to replicate your most essential reporting in your new home, and how to level up these reports using features unique to Adobe Analytics. The world is your oyster – go forth and analyze.

We hope we have managed to impart useful information to you in this short time, and we hope this workbook will help you retain what you learned and point your way to additional resources that can expand your knowledge. We are eager to hear your feedback and continue the conversation! Please visit the Forum page; we'll be keeping our eyes out for your comments and would love to chat with you about how to get Adobe Analytics working better for your organization. It's what we do!

David Sprinkle<br>
Chief Analytics Officer, Acronym<br>
<dsprinkle@acronym.com>

Janelle Olmer<br>
Director, Digital Analytics, Acronym<br>
<jolmer@acronym.com><br>
\#measure Slack: jeolmer

*Acronym has been helping brands design, deploy, maximize, and maintain their digital analytics infrastructure since 2008. Our analytics practice is made up of certified experts with extensive experience in all major tools including Adobe Analytics, Target, DTM, Launch, Media Optimizer and Ad Cloud. We have been an Adobe Solution Partner since 2012.*

# Appendix

## Key Concepts

Here's a basic primer on some core concepts and terms we've used during this lab. For more info, Adobe's built-in help documentation is pretty good. You can search it from anywhere in Analytics by clicking the "?" icon in the top right of the interface:

![42](./images/image42.png)

- **Dimensions and Metrics –** Every report includes at least one dimension and one metric. Metrics *count*, while dimensions *describe*. Another way to think about it is that dimensions are usually words, while metrics are always numbers.  

  For example, if you're looking at report showing how much revenue you generated in each US state, "state" is the dimension and "revenue" is the metric. Simple enough! Depending on where you're looking, Adobe sometimes called dimensions "variables" or "breakdowns" to keep you on your toes.

- **Traffic metrics vs. Conversion metrics –** This is kind of a legacy thing but it still crops up some places. Traffic metrics count the things you know just by having Adobe's global code on your site: page views, visits, time spent, entries, exits, bounces, and visitors.  

  Conversion metrics indicate a visitor did something you care about—like filling out a form, checking loan rates, or buying something. These are specific to your business, so they will vary with each implementation.

- **Traffic dimensions**, sometimes called "props" for technical reasons, are a type of dimension that only lets you put traffic metrics on the report. If you're deploying a new implementation, we don't recommend using these except in a few special circumstances. They suck.

- **Conversion dimensions**, sometimes called "eVars" because of the Illuminati + technical reasons, let you put both traffic and conversion metrics on the same report. These are better. Use these instead. One key feature of conversion dimensions is that they can "remember" values after they're set, for a customizable amount of time.  

  This is similar to the concept of "scope" for custom dimensions in GA, but you can customize the persistence with more flexibility in Adobe. For instance, you might want a campaign code to persist for 7 days and get credit for all downstream activity during that time. Or, you might want to define a video name when the video is first played and then expire it when the video is complete.  

  Conversion dimensions have a few other important settings, like attribution and the undeservedly dreaded merchandising settings, but you'll have to look those up yourself.

- **Events** – An "event" is Adobe's term for a conversion metric. It is, simply, a Thing That Happened. This is very different from a GA event, which is a thing that happened that includes both dimensional (Category, Action, Label) and metrical data (Total Events, Unique Events, Value).  

  Adobe events can be configured to either just count up +1 each time something happens (equivalent to "total events" in GA), or only count once per visit (equivalent to "unique events" in GA), or only count once ever using a technique called *serialization* (which GA can't even manage to do for purchases, for some reason).

  > **PRO TIP:** Most of the time, events will be set up to count every time something happens. When setting up a new event, we strongly recommend specifying if this is not the case in either the event name or description (e.g., "Visits w/Article View").

- **Page Names** – Most analytics tools rely on URLs to identify pages. Adobe can certainly report on URLs (though not by default, FYI), but prefers to rely on a concept called Page Names that lets you provide more user-friendly customized names for each page.  

  This can be handy if you change your URLs for SEO purposes, but want historical continuity in your reports; or, if dynamic URL parameters create multiple unique URLs for the same page. It can be a little daunting to figure out a Page Name strategy when you first launch, but the time is worth it.

  > **PRO TIP:** Many organizations rely on their URLs to some degree to define Page Names. That's fine, but also keep in mind that one benefit of Page Names is the ability to maintain a consistent value in Analytics even if the URL of the page changes. Try to keep that in mind when designing your implementation—for instance, maybe copy your URLs into a separate field in your CMS when you first deploy and then make sure that field stays the same if you change the visible URL for the page.

- **Server Calls vs. Page Views –** As you may already know, what you pay Adobe for Analytics is based on something called server calls. A server call is simply a "ping" from your site or app to Adobe's servers—it's you sending data to them. The more data you want them to store and crunch, the more resources they have to commit, so the more they charge you. Fair enough.  

  Server calls are not always the same thing as page views. Some things you want to track really shouldn't count as a page view: for example, video views; clicks on a download link; expanding a "more info" accordion; interacting with a mortgage calculator widget.  

  In Adobe-speak, these interactions are called "non-page view server calls". (The product marketing team was unfortunately away on a team building retreat the day that name was decided.) More technically, a page view is an "s.t call", while the other thing is an "s.tl call". This is roughly equivalent to page vs. event calls in GA.

  It's important to understand that both types of server calls exist and affect your overall server call quota, because in some cases you may have a lot of non-page view server calls on your site or app. (This is *especially* true for mobile apps.) Total server calls is not a default metric, so make sure you look at the billing logs instead of relying on a page views report to keep tabs on your usage and avoid unpleasant surprises.

- **Serialization –** For key flows on your site, like your main conversion funnel, it may be important for analysis to be able to deduplicate how many times a person hits each step. Sites with shopping carts or multi-step forms may allow visitors to return later and pick up where they left off.

  In addition to letting you build visit- and visitor-based metrics around this (i.e. "unique carts"), which can deduplicate for a single device, Adobe has a feature called *serialization* that lets you send a unique ID for each cart/application/etc. that Adobe will use to deduplicate any conversion event, across all devices, forever. This is pretty dang cool.

  > **PRO TIP:** Not sure if you should serialize or not? You have 1,000 events to play with—set up one group of events that's serialized and one that's not, and figure it out later.

## Key Metric Definitions

- **Page Views** – Pretty much all tools call these page views (or pageviews). So hey, you already know that one!

- **Visits** – Similar to Sessions in GA. A series of pings to Adobe from a browser, which ends if there is 30 minutes of inactivity. Note that unlike in GA, a new visit does not trigger if the visitor re-enters the site from a new traffic source during their visit.

- **Unique Visitors** – People, or to be more precise unique visitor ID cookies. Similar to Users in GA. You may also see metrics with names like "Daily Unique Visitors" or "Monthly Unique Visitors" in places other than Analysis Workspace; generally, ignore these. They're mostly a legacy thing and they're more confusing than helpful in most circumstances.

- **Entries** **& Exits** –The first and last value recorded *for that dimension* during a visit. These can get a little tricky! Just because it was the first or last value for that dimension doesn't mean it happened on the first or last page view of a visit.

  On the Pages report, these work about how you'd expect, because you send a page name on every page view. But don't freak out by putting Exits on a search terms report and think everybody searching for "blue jeans" immediately bailed. It just means that was the last search term during the visit.

- **Bounce Rate** – Bounces divided by Entries. Note that Adobe does not have the concept of a "non-interaction event" (though it would be a lot cooler if they did), so if you're tracking an automatic popup on your homepage or an auto-playing video, those won't count as bounces. There's another metric called *single page visits* you can use to correct for this kind of thing.  

  If you’re comparing your Bounce Rate in AA against Bounce Rate in GA, chances are your Bounce Rate in AA is lower. That’s because “Bounce” visits in GA exclude visits who only viewed one page and triggered non-interaction events; in AA, “bounces” exclude visits who viewed one page and triggered additional events. If you want to compare apples to apples, compare GA Bounces and AA Single Page Visits.

- **Instances** – The number of times that value was sent to Adobe, either as part of a page view or a "non page view server call", such as a tracked link click. Some tools call this "hits." We actually use this one a lot.

- **Occurrences** – Don't use Occurrences. It's stupid and confusing, and yet it's the default metric in Workspace. Just tell everyone to kill it with extreme prejudice and save yourself.

## Saving and Socializing Your Report

We hope that over the course of this lab, we’ve given you good ideas on how to use Adobe Analytics to analyze and report on your website & app data. If you are fearful of having to recreate reports in Workspace every time you want to look at them, or if you are fearful of having to teach users how to recreate reports themselves … fear not! Let’s run through a few of the standard options to store and distribute Analysis Workspace Projects.

### Save your project!

Even if you don’t want to distribute your report, you do not have to replicate your work every time you want to look at it.

Go to Project menu and click “Save.” (I bet there's a keyboard shortcut for this, too.) This means that the project is saved in your account and you can come back to it whenever you would like. It is not shared with any other users unless you explicitly grant them access.

If you haven’t already, you’ll be asked to name your project. Projects tend to accumulate, so use something memorable and unique like “David’s Nifty Page Contribution Report – Adobe Summit 2019.”

### Share this report with other Adobe Analytics users.

Tell the world! Underneath the “Share” menu in the light-grey header, you can share with individual users and user groups (if you've set groups up).  
  
![43](./images/image43.png)

### Point Users Directly to *This Specific Report*

Before long, you will probably have many projects in Analysis Workspace – some that have been shared with you and some that you have created yourself. Instead of scrolling through a list of projects or pointing colleagues to do the same, we often send users short links that will drop users directly into the report that we’re looking at. Unfortunately, copying the browser URL doesn’t work.  
  
To generate a short link, go to Share > Get Project Link. It doesn’t look like much, but these things are great. We use these short links *all the time*.  
  
![44](./images/image44.png)  
  
>**PRO TIP:** If you're presenting data in a presentation, put the short link back to the report in the slide comments to make it easy to pull the same data again next quarter or to pull it up during that meeting where your boss doesn't believe you.

### Download This Report

We have come to terms with the fact that not everybody will necessarily log in to Adobe to view our handiwork. Instead of taking screenshots, you can export this project as a PDF and your recipient will be able to experience this report in its full glory. Go to Project > Download PDF. Make a mental note of the hotkey and reassure yourself that you will definitely remember it next time.  
  
![45](./images/image45.png)

### Email this Report (Once or on a Recurring Basis!)

Head on back to the Share menu. Click Send File Now to email this to recipients once, or click Send File On Schedule to send on a recurring basis.  
  
>**PRO TIP:** Check to make sure that your date range is dynamic (“Rolling”) when you set recurring reports, otherwise you’ll receive the same date range every time it sends. **  
  
![46](./images/image46.png)

![47](./images/image47.png)

### Manage Shared Reports

Before long, you will need to manage the reports that you are sharing with others (or that others are sharing with you). Go to Components > Projects to manage your dashboards, to do things Delete, Share, or Tag in Bulk.

## Bonus Calculated Metrics!

This lab is about migrating to Adobe Analytics tools from other platforms. We had 90 minutes. We couldn't possibly cover everything—we barely scratched the surface.

We tried to focus on "lowest common denominator" knowledge and workflows that we hope are relevant to the greatest number of participants, and we have tried to shine lights on a number of concepts that you can explore further. We apologize that we couldn't cover everything you'd like to learn about – there is more that we would have loved to share with you!

As special thanks for sticking around, here are a few Calculated Metric exercises that didn’t quite make the final cut. We’ve tried to be as explicit about how to build these as possible so that you can easily replicate these within your organization!

### “Assisted / Last Click Conversions” Calculated Metric

An “Assisted/Last Click Online Orders” metric can be useful to understand at a glance whether a traffic channel (or other dimension value) is more likely to close a sale or to contribute earlier in the user’s conversion path (assist in a sale). It’s that one on the Google Analytics Assisted Conversion report that most marketers tend to focus on, since it’s a great way of quantifying a channel’s likelihood to open, close, or participate in a sale (or other conversion type).

Open up the Calculated Metric Builder, then drag and drop “Order Assists (Report Participation)” and “Online Orders” into the builder. Set the metric type to Numeric, with two decimal places. Your new Calculated Metric should look like this:

![48](./images/image48.png)

On a report, the metric looks like this:

![49](./images/image49.png)

When the value of this Calculated Metric is between 1 and 0, the channel is more likely to close than to assist. The closer to 0 this is, the more that is true. If it’s 1 on-the-dot, the channel is equally likely to either assist or close. If it’s greater than 1, the channel is more likely to assist than close. The further away from 1 it is, the more likely it is to assist. Yes, this aligns with Google’s definition.

### “Visits with Product Views” Calculated Metric

Remember when we mentioned that Calculated Metrics were really powerful, that they included the ability to do much more beyond basic arithmetic? Let’s create a metric for “Visits with Product Views” that will work similarly to how Product View Goals in Google Analytics work: simply counting the number of visits that included a Product View.  
  
Start by clicking to open the Calculated Metric Builder to create a Calculated Metric from scratch. Name this “Visits with Product Views.”

This is going to sound counter-intuitive, but now let’s also create a Segment directly within the Calculated Metric – you can do that directly from within the left rail! You could technically build the Segment first, then build the Calculated Metric … but more often than not, we forget to build the segment first (and sometimes there are ways to get around needing a segment altogether). So, we have committed to always creating the Segment after opening the blank metric in our workflow!

![50](./images/image50.png)

Name this new segment “Product View Instances”, add Product Views to the segment definition, change the criteria to “exists”, and ensure that the scope is set to “Hit.” Click Save to continue.

![51](./images/image51.png)

Now, from the left rail within the Calculated Metric Builder, find the segment “Product View Instances” that you just built. This will be in blue. Drag and drop it into the Calculated Metric definition. Your screen should look like this:

![52](./images/image52.png)

Find the Visits metric from the left rail and drop it into the segment. Your screen should look like this:

![53](./images/image53.png)

Click Save, then add the new Calculated Metric to a report and revel in your work.  

![54](./images/image54.png)

As you might have already guessed, this can be helpful when we’re looking to understand which channels are most likely to generate *qualified* visits – that is to say, most likely to generate visits that are at least looking at products.

You could read the above like: “of the 75K visits from Email, 23K viewed products. There were 41K total views of products generated from Emails.”

### “Product View Rate” Calculated Metric

If you suspected that “Visits with Product Views” might be a good way to start to look at the conversion funnel on a Channel-by-Channel basis, then you are probably also interested in creating an index metric to show the percentage of total visits from each channel to look at products.  
  
By this point, we’ve gone through all the steps required to create this “Product View Rate” metric. See if you can create this on your own!  
  
You should be able to gut-check that this is correct by dividing “Product View Visits” by “Visits” manually. Remember: gut-checking everything that you create in Analysis Workspace (no matter how simple it seems) is a must!
