# How to switch to Adobe Analytics

Congratulations on the decision to switch to Adobe Analytics! You’ve taken your first step into a larger world. Although no two analytics tools are the same, the leading web analytics tools (Adobe Analytics and Google Analytics) share enough common functionality that you can quickly learn how to get meaningful insights into your business.

This guide presents common report types that help you to learn core concepts and workflows in Adobe Analytics, focusing on key similarities and differences between Adobe and other popular tools. This guide is designed for analysts who are familiar with basic digital analytics concepts, but new to Adobe Analytics.

In this guide, you will learn:

1. Core Adobe Analytics concepts and capabilities and how they relate to other analytics platforms
1. How to translate specific workflows and terminology into Adobe Analytics
1. A few advanced capabilities unique to Adobe Analytics

Additionally, this guide provides step-by-step instructions for working with features in the following report types:

* Site Content Reports
* Marketing Channels Reports
* Products and Funnel Reports

## Requirements

You can read and learn from this guide with no special requirements. However, to perform the steps shown in this guide yourself, you will need the following:

1. Access to an existing Adobe Analytics account, or a demo account
1. A basic understanding of web analytics concepts, such as page views, bounce rates, conversions, and funnels
1. Access to an instance of Analysis Workspace with sufficient privileges to create and share segments and calculated metrics
1. Administrator or developer help, in some cases, to fully implement your Adobe Analytics account.

Make sure that your Analytics is fully implemented with web properties.

## Get started in Adobe Analytics

To get started in Adobe Analytics:

1. [Log in to Adobe Experience Cloud](https://marketing.adobe.com/resources/help/en_US/analytics/getting-started/analytics-navigation.html).
  
1. [Navigate to Adobe Analytics](https://marketing.adobe.com/resources/help/en_US/analytics/getting-started/analytics-navigation.html) and Analysis Workspace.

## Analytics visual tools

Adobe Analytics provides two different visual tools to analyze your business: Analysis Workspace and Reports and Analytics. In Analysis Workspace, you work with visualizations that correspond to reports in different tools. These visualizations show key metrics for your web business. The visualizations are not only more flexible and robust in displaying metrics, they are also easier to create. They also provide much more detail than traditional reports. You create visualizations by dragging and dropping data tables, dimensions, metrics, segments, and time periods on the Analysis Workspace user interface. 

You can also extend visualizations with right-click options. For more information on the features of Analysis Workspace visualizations, see the [Analysis Workspace Overview](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/). Adobe's Reports and Analytics capabilities also correspond with report types in other tools. Both tools offer unique capabilities that go beyond simply measuring page traffic so that you can better understand how pages convert users. 

## Site content reports

Site content reports include ways to analyze page traffic and page conversions and to create calculated metrics and *assist* metrics. This section explains how site content reports work in Adobe Analytics and shows the tools and interface for creating the reports and visualizations. 

### All Pages Report

You can construct either a report or a visualization in Analytics that is similar to an **All Pages Report** in other tools. This report provides content performance--one of the fundamentals of web analytics. This section describes the following:

1. How to construct a **Pages** Report with the Analytics report interface
1. How to construct a **Page Performance** visualization in Analysis Workspace similar to an All Pages Report

Additionally, by creating these in Analytics, you learn:

1. How to navigate the reporting interface to measure page traffic
1. Key Adobe Analytics concepts, such as report suites, dimensions, and metrics
1. How to quickly customize reports
1. How the content on your pages contributes to conversion
1. How to share your report with others

#### Construct a Pages report

To construct this report: 

1. In Adobe Analytics, click the **Reports** tab and then click **View All Reports**. Note the menu showing all the reports set up in your account. These menus, and the reports within them, are your reports suite and are customized to your specific Adobe Analytics implementation.

*Reports Tab Image Here*

2. Click **Content** > **Pages**. The **Pages** report appears and shows [dimensions](https://marketing.adobe.com/resources/help/en_US/reference/dimensions.html), [metrics](https://marketing.adobe.com/resources/help/en_US/sc/implement/ref-metrics.html), and page names.

*Pages Report Image Here*

#### Create a visualization for Pages

Analysis Workspace provides an easier way to see all types of available dimensions and metrics. It functions similar to creating basic reports but greatly enhances the speed, flexibility, and customizability of visualizing and analyzing your data. 

In Analysis Workspace, the **Page Performance** visualization shows traffic metrics for the **Page** dimension.

To create a **Page Performance** visualization in Analysis Workspace:

1. Click **Workspace** at the top left of the Analytics screen.
1. Click the blue **Create New Project** button. 
1. For your project, you can use a Template Project or a Blank Project. A blank project is a blank canvas you use to build your visualization. A template is a set of pre-configured reports, components, and visualizations. [Templates are helpful starting points](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html) for building larger dashboards or analyses, and to help others see your insights more quickly. If your organization has an existing template, you can click that and explore the details that follow. Otherwise, select the **Content Consumption-Web** template and then click **Create**. 

*Template selection image here*

4. Scroll down to find the **Top Pages** section on the **Content Consumption** screen. Your template includes visualization starting points, including this one for page content. The information in the visualizations is for demonstration purposes only and does not reflect any real data. Although many **Content** screens [often show dashboards](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/) at the top that summarize numerous metrics, this template first shows a flow visualization at the top. This screen can be customized to present visualizations in any order.

*Top Pages Visualization Image Here*

***About Report Suites***

For this template, the fictitious data is based on the report suite showing in the **Report Suite Selector**. Click on the selector to choose a different report suite or continue with the `Cross-Industry Matisoft Data` report suite that appears with the template. None of the report suites associated with the templates have real data.

*Report Suite Selector image here*

In Adobe Analytics, a report suite is the repository where you send your data and from which you pull reports. Usually, a report suite collects data from one website. This is similar to a **View** or a **Profile** in other analytics tools.

Your organization may have different report suites set up for different sites and apps. Check with your administrator to understand where you should be pulling reports from.

One key difference between Adobe's data collection method and many other tools is that you specify which report suite(s) to send data to when you send the data. This is different from other tools that typically send all your data to one collection location and then filter that down to create different views or profiles via the admin interface.

You can also build [virtual](https://marketing.adobe.com/resources/help/en_US/reference/virtual-report-suites.html) report suites, which let you build filtered views from a normal report suite.

For more information on report suites, see the [Report Suites Manager](https://marketing.adobe.com/resources/help/en_US/reference/report_suites_admin.html) help.

### Using Workspace toolbars

Analysis Workspace includes three toolbars that appear according to the icon you select on the far left of the screen.

*Toolbar icons image here*

* Panels toolbar: Shows options for creating the panels that hold your visualizations
* Visualizations toolbar: Shows options for structuring or customizing your visualizations according to form
* Components toolbar: Shows options for adding components to visualizations

### Customize your visualizations

The following section describes ways to customize your screen and visualizations. The typical screen actions associated with customizing your visualizations include dragging and dropping screen elements and right-clicking visualization items to select other options and actions. 

1. To customize the name of this project, click the title in the upper left of the screen and type the new name.

1. To change the settings of your project, or to save, share, and edit it, click the applicable menu beneath the title and select the applicable option. Each menu item includes [keyboard shortcuts](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/fa_shortcut_keys.html) as well.

*Project title and menus image here*

3. On the left side of the screen, note the **Component** toolbar, which contains groupings for **Dimensions**, **Metrics**, **Segments**, and **Time**. These components are all available to use in your visualizations. The **Dimensions** grouping is expandable into sub-components. Under **Dimensions**, click the **Page** arrow **>** that appears when you hover over it. The **Page Items** then appear as sub-components.

*Page arrow image here*

4. Select the date range for your visualization. Click the Date Range in the upper right of the screen to open the Date Picker. The range you select here applies to the entire panel in this Analysis Workspace project. This template defaults to the last month across all panels.

*Date Picker image here*

***About Panels***

A Panel is a collection of visualizations. You might have many visualizations that you want to group in different categories, but also keep in the same project. To do this, you can create multiple panels that  hold the visualizations that you move to them. For example, the Content Consumption template contains only one panel--called Content Consumption.

*Content Consumption panel image here*

If you click the drop down arrow on the panel, it collapses to show other panels you have created (in this case, none). If you click the arrow again, it expands the panel to fully display on the screen. To add more panels, click **Insert** > **New Blank Panel** and choose the type of panel you want to add. For more information on panels, see the [Panels](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/panels.html) help.

### Understanding Content Reports

To understand the elements in the page performance visualization (entitled **Top Pages** in this template), refer to the following image:

*Pages report image here*

This type of visualization is called a [Freeform Table](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/freeform-table.html). You can easily build or modify these tables by dragging and dropping elements on to them. This table shows traffic metrics for the **Pages** dimension, including the following:

* [Page Views](https://marketing.adobe.com/resources/help/en_US/reference/metrics_page_view.html)
* [Visits](https://marketing.adobe.com/resources/help/en_US/reference/metrics_visit.html)
* [Time Spent per Visit](https://marketing.adobe.com/resources/help/en_US/reference/metrics_time_spent.html)
* [Entries](https://marketing.adobe.com/resources/help/en_US/reference/metrics_entries.html)
* [Bounce Rate](https://marketing.adobe.com/resources/help/en_US/reference/metrics_bounce_rate.html)
* [Exit Rate](https://marketing.adobe.com/resources/help/en_US/reference/metrics_exits.html)

For more metrics descriptions, see the [Metrics](https://marketing.adobe.com/resources/help/en_US/reference/metrics.html) help topic.

***About Bounce Rate***

Bounce Rate is a common KPI that is used to help measure the effectiveness and the relevance of landing pages in most analytics tools. This is commonly defined as visits that enter the website but do not include a click to another page. For Adobe Analytics, this metric does not include visits that include a click on the landing page. Interactions like downloads, video plays, and navigation may cause the bounce rate to be different from other tools.

To compare like metrics across tools, use the **Single Page Visits** metric in Adobe Analytics instead of Bounces. The **Single Page Visits** metric includes the total number of visits that only included one-page view, or visits that enter the website but do not include a click to another page.

### Create a calculated metric

Most out-of-the box metrics in Adobe Analytics provide counts of things: how many pages viewed, how many files downloaded, how many seconds visitors spend on the site. Other tools, Google Analytics in particular, often show *index metrics* or *calculated metrics* by default. Adobe Analytics includes a dedicated calculated metrics builder that includes functionality for advanced mathematical metrics. While other tools let you create basic calculated metrics that divide, multiply, add, and subtract, Adobe's allows you to do this as well as add segments for calculating mean, standard deviation, variance, and others.

Index metrics in other tools are typically limited to dividing counts of one thing by counts of another thing: for example, you might divide Conversions by Visits to get Conversion Rate. These metrics are helpful when you are trying to compare the effectiveness of items with different volumes. For example, organic search might bring in ten times the traffic of social media, but conversion rates might show that social media converts at a far higher rate than organic search. Adobe's calculated metric builder is especially helpful in cases like this. 

If you do not already have a calculated metric in your project, you can create one by following these steps:

1. On the **Components** toolbar, click the **+** next to the **Metrics** component box.
1. Add the following title: **Page Views per Visit**.
1. For **Format**, select **Decimal**.
1. Increase the **Decimal Places** to 2. 
1. Drag the **Page Views** metric to the **Definition** box. Then drag the **Visits/Vistors** metric to the same box under the first metric (wait until the blue line appears to drop it).
1. Between the two metrics listed in the **Definition**, select the Divide operator (if not already selected).
1. Click **Save**. Note that the new calculated metric is added to the **Metrics** box. Anytime you make a change to the metric definition.

### Add metrics to visualizations

To add your new calculated metric to the page performance visualization (or **Top Pages** free-form table):

1. Expand the **Content Consumption** panel, if not already expanded. 
1. Drag your new calculated metric from the **Metrics** box on the toolbar to the page performance freeform table header. The blue flag that appears as you drag the metric indicates where the column is added when you drop it. The visualization now includes a new column with new metric data.

### Page value: add conversion metrics

Conversion metrics show data about success events, such as purchases, downloads, or any other action that you want users to take on your website. To add conversion metrics to the page performance visualization (or **Top Pages** free-form table) you can refer to the following example procedure:

1. In the **Components** search box, type `Online Revenue`.
2. Drag and add it next to the metrics on the page performance table.
3. Sort the pages in descending order, based on how much online revenue they generated. To do this, hover between the trend line and the online revenue totals at the top of the column. When the downward arrow appears, click it. To sort it back in ascending order, click the upward arrow that appears when you hover in the same place.

Note that online revenue is attributed to the order confirmation page. This is because the pages report uses a *Last Touch attribution* model. 

### Page value: add participation metrics

[Participation](https://marketing.adobe.com/resources/help/en_US/analytics/calcmetrics/participation_metric.html) is a unique type of attribution available for all metrics in Adobe Analytics. Participation models assign full credit for conversions to all dimension values that a user touched prior to the conversion. For instance, if a user spends $100 on your site and hits 10 pages during the visit, Revenue Participation gives $100 credit to each of those 10 pages. You can set the look-back window to be during the same visit, or for the same visitor during the reporting date range. This not only useful, but also critical when trying to accurately understand how different pages, campaigns, search terms, etc. contribute to ultimate conversion.

Because full credit is assigned to each dimensional value the visitor hits along the way, it is not possible to provide a sum for participation metrics to understand the total number of conversions. Such a count would be too high to be useful. Instead, you can use the value in the column header, which deduplicates the data. Participation metrics are retroactive, applying the new metric to past data as specified.

Your administrator can also set up calculated participation metrics for your organization.

To add a participation metric:

1. Create a new metric in the Calculated Metrics Builder, as performed previously.
1. Drag the success event **Orders** into the **Definition** box.
1. Change the attribution model of that event to **Participation** under the Settings gear. Choose **Visit** lookback. 
1. Save the metric.
1. Drag the calculated metric to the pages report.

You can also create participation that mimics the Total Page Value, as found in other tools, except that you can put participation in any report you want, for any conversion metric you track. For example, you can use Calculated Metrics to divide **Online Revenue (Participation)** by **Visits**. Similarly, you can also divide **Online Orders (Participation)** by **Visits** to understand the page conversion rate. Unlike the metric in other tools, which is bounded to the Page Value report, you can use this for *any metric in Adobe Analytics.*

### Content velocity

Content Velocity is a pre-set calculated metric in Analysis Workspace. This metric determines how many page views each page generates. It is calculated by dividing Page Views (Participation) by Page Views. This can be a great way of determining which content is most likely to generate engagement with additional content. 

## Marketing channels reports

In Analysis Workspace, the Marketing Channels report shows how users find your website. This includes both tagged (paid search, email) and untagged (natural search, organic social referrers) traffic. If you want a pie-chart of traffic, of online orders, or of online revenue, the marketing channels report is best-suited for these purposes. Compared to other tools, Adobe Analytics provides more flexibility on how to measure campaigns and traffic channels. This section shows how you can use Adobe Analytics tools to analyze campaign performance as well as how to analyze campaign performance to conversions. Also, it explains how to measure channels that *assist* conversions and how to use other unique Analytics features that enhance your insights into these reports.

***About first and last touch channels***

The **Components** menu includes a Last Touch Channel and a First Touch Channel report. In Workspace, the Last Touch Channel is the same as Marketing Channel. The First Touch Channel is the Acquisition Channel. 


**Campaign tracking in Adobe Analytics**

Other analytics tools have strict guidelines on how to tag campaign URLs. You must use specific URL parameters, such as `utm_campaign`, `WT.mc_id`, `cm_mmc`, etc. With Adobe Analytics, you have control over which parameters are used to identify campaigns. For example, you can set up Adobe to look for whatever you were using with your old platform, so you do not need to re-tag your URLs. You can also set things up to look first for a new parameter, like `cid=`, but then return to whatever you used previously. This helps if you want to simplify tagging requirements but also want to make sure old campaigns still floating around get tracked.
  
**Traffic source attribution in Adobe Analytics**

Adobe includes many reports for traffic source attribution. For best results, organizations should implement them intelligently and curate them conscientiously. It also helps to enable the Marketing Channels reports and then hide other traffic source reports that might work at cross purposes. Perhaps this might include hiding referring domains or search engines.

When setting up your marketing channels, review the [default list of social networks](https://helpx.adobe.com/analytics/kb/list-social-networks.html):

On the Marketing Channels Report, find the **Marketing Channel Instances** metric.

*Marketing Channel Instance image here*

Instances show the total number of times that a user clicked to your website and the Marketing Channel changed. Similar to its use in other analytic tools, the Marketing Channel persists beyond the initial click-through until the user clicks through from another campaign or referring domain. *Visits* here means the total number of visits where the most recent Marketing Channel was, such as email. Therefore, *Marketing Channel Instances* here gives the total number of clicks from email.  
  
Adobe also gives you more flexibility for your attribution window than most other tools. The windows are not channel-specific, but the lookback window is up to you. No six-month attribution window limit exists, as in other analytics tools. You will see a larger percentage of Direct users in Adobe than in others, but this is easily managed with tagged campaigns.

### Analyze campaign performance with marketing channels

It is important to understand not just the total number of Paid Search visits and conversions, but also which campaigns drove those conversions. To look deeper into individual channel performance, use the Marketing Channel Detail report. This is generally the only report that has the same attribution model as Marketing Channels.
  
There may be additional reports in your implementation based on Marketing Channel detail – check with your administrator to see which are available and best to use.  
  
The Marketing Channel Detail report shows you a second-level of granularity for each Marketing Channel. This is customized to each Channel, in each Adobe Analytics implementation. Typically, this is set to show the campaign tracking code for all tagged marketing channels, the referrer for all channels--based on referrers (such as organic social or organic search), and the entry page name when neither of these exist (such as direct or mobile app). This is also worth verifying with your Analytics administrator. 

*Add Marketing Channel Detail as a Secondary Dimension*

To add this, in **Component** search, type `Marketing Channel Detail`. Drag and drop this component on top of **Email**.

You can add breakdowns to multiple primary dimensions in this report, and in the same way that you added a breakdown to the primary dimension, you can also break down secondary dimensions (and tertiary dimensions, and beyond). This is a useful way to dive deep into your data.

### Analyze total channel contribution to conversions

Previously, the Participation attribution model on the **Pages** report helped us to understand the average value of specific content. Similarly, we can attribute all Online Revenue to every page that a user interacted with during a visit prior to converting. This can be used on any dimension to attribute all Online Revenue to every dimension value that a user touches during their visit. This is how the *Visit Participation* model works.

Similarly, *Report Participation* allows you to attribute revenue back to all dimension values that a user touched prior to conversion across the whole report date range. Report Participation is an *Any Touch* attribution model.

*Add Online Orders (Report Participation) to the last touch channel report*

1. Find the **Online Orders (Report Participation)** metric.
2. Add it to the Marketing Channels Report.

*image here*

You can read this report as: *Each click (instances) represents this amount from Print ads. Print ads were the last-touch channel for 416 total Online Orders, but participated in 5.3K total Online Orders (13% of site total).*

Remember, as with the **Visit Participation** metric, these values cannot be summed. The same order in Participation models is attributed to multiple Marketing Channels.

### Analyze how channels assist conversions

If you want to see the total number of Online Orders that each channel participated in but was not the last touch--sometimes referred to as *assists*, you can use Adobe's Attribution IQ. This feature allows for advanced attribution modeling. To use this feature:

1. Open the Calculated Metric Builder.
1. Name the metric `Online Order Assists (Report Participation)`.
1. Drag **Online Orders** into the definition.
1. Hover over the right side of the metric in the definition, then click on the gear icon.
1. Click **Use non-default attribution model**.
1. Set the **Model** to **Participation**.
1. Select **Visitor (Reporting Window)** as the Lookback Window.
1. Click **Apply**. Your metric definition should look like this:

*image here*

9. Find **Online Orders** in the toolbar and add it underneath the **Online Orders (Participation/Visitor)** component.
10. Click to change the operator from Divide to Subtract.
11. Save the calculated metric and add it to the Marketing Channels Report.

*image here*

This shows all online orders that each channel participated in but was not the last-touch channel. 

If you sum up **Online Orders** with **Online Order Assists**, it should equal **Online Orders (Report Participation).**

In other analytics tools, you can only do this for *eCommerce + Goals for Channels & Campaigns*. In Adobe Analytics, you can do this for *all* dimension values and for *all* events.

### Attribution IQ

Adobe's Attribution IQ feature allows you to apply custom attribution models to any of your reports. This is unique only to Adobe Analytics. You can use this to understand how different marketing efforts initiate, assist, and close deals for you. Additionally, it can provide insights on linear allocation, J-Curves, time decay, and attribution models within attribution models. To read more on this feature, see [Attribution IQ help](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/attribution.html).

### Integrate media data

Adobe provides numerous ways to integrate your media data into Analytics. This includes the integration with Adobe Media Optimizer and Adobe Ad Cloud, as well as Target and Campaign. Analytics includes a data connector for DoubleClick, which allows you to pull in DoubleClick data, including view-through conversions. Many third-party email platforms have Data Connectors of their own. Additionally, Adobe's provides a feature, called *Advertising Analytics*, which lets you pull impression, click, and cost data from Google, Bing, and Yahoo!.

## Products and funnel reports

If you are using a different analytics tool, you probably must find work-arounds to report on your sales funnels *exactly* how they should be measured. With Adobe Analytics, advanced analysis functionality is already included, which allows you to define unlimited and customizable product and funnel reports for your eCommerce and content sites. This section shows you how to measure product performance by using a standard eCommerce checkout funnel. 

The instructions also include:

1. New ways to build ad hoc product and conversion funnel reports
2. How to pass visitor data into other Adobe solutions for retargeting
3. Options to include offline data in Adobe Analytics


### Analyze product performance for desktop visitors

To find product performance for desktop visitors:

1. Find the **Desktop Visitors** [segment](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_overview.html) in the **Components** toolbar.
2. Preview the segment definition by clicking the info icon in the component. Hover over component to see an **i** icon appear in the right corner. Click this icon to open a preview of the segment definition, including a graph of how many visits, visitors, and page views are included in this segment. The **Desktop Visitors** segment uses the criteria `Mobile Device Type = Other`. 
3. Drag **Desktop Visits** to the top of the panel

The top left side of the panel shows a segment that is already applied to this report. This segment filters data for just website (excluding mobile app) visits. When you apply two segments to a report, Adobe Analytics shows only data that matches both criteria. This should result in a product performance report filtered for Desktop visitors only.

***About unspecified rows***

On some reports you may see a row labeled **Unspecified**, or **None**. You can ignore these rows, generally. Adobe likes to give you all data for every metric on your report, even if there's no associated dimension value for it. This is to provide context for your data. For example, if a Products report contains a metric such as **Occurrences** on it and it shows  **Unspecified**, this might reflect actions on a site that did not involve a product. But if **Unspecified** shows up getting credit for product views or cart additions, that may be an implementation issue.

### Analyze conversion fallout from category pages

A Fallout Report in Adobe Analytics is a dynamic visualization showing how many visits or visitors complete specific actions in sequence. The most common example is an eCommerce conversion funnel: how many people view products, add items to their cart, begin checkout, and purchase. But fallout reports can also show how people go through sequences of pages or page types, or how visitors engage with different campaigns and channels.

To analyze fallout with the eCommerce Conversion Funnel, scroll to find the Product Conversion Funnel Report.

After scrolling down to find the Product Conversion Funnel report, you might try to compare the data here against the Products Performance Report. You might notice that they do not match. The Product Performance Report shows the total number of Product Views, Cart Additions, and Online Orders. By contrast, the fallout visualization shows the total number of *visitors* who viewed products, the total number of *visitors* who added items to their cart after viewing products, and the total number of visitors who bought products online after having viewed products and adding items to their cart.  

The fallout visualization enforces sequence and deduplicates. The freeform table does neither.

Fallout reports are also helpful because you are not limited to using either metrics or dimensions in your step definitions. You can use both together.

To take a closer look at the fallout from Product Category (Product Browse Grid) pages:


1. Click the **Page Type** dimension.
1. Hover over the dimension and click into the right-facing arrow that appears.
1. On the menu that appears, click the dimension value most appropriate. The menu shows the most common Page Type values in the last six months. You can use these dimension values the same way that you can use Segments, Dimensions, and Metrics in the report.
1. Find **Category** and then drag and drop this on top of the **Product Views exist** step. Your report should appear as follows:

*Image here*

To see all visitors who go to Category pages and the product fallout from those pages:

1. Change Container from Visitor to Visit Scope. By default, this shows you the path of Unique Visitors and includes All Visits as the first touchpoint.   
1. To change the default, click the gear icon in the upper right-hand corner of the Fallout report. This opens the Fallout Settings.
1. Toggle the container from Visitor to Visit to show the total number of visits that go through your sequence during a single visit, instead of the total number of visitors who go through your sequence during the report timeframe. 

For Category Page Fallout, you can change this to be **Visit** scoped.

To start funnel at Category Visits, in the same settings menu, un-check the option box for `Show All Visits` as the first touchpoint. This removes the bar at the start of the funnel that shows you the total number of Visits/Visitors, making the first step of your sequence Category Page Visits.  
  
*image*

### Cart abandonment segments

The Adobe Experience Cloud makes it simple to turn segments in Analytics into Audiences in other Adobe Marketing Cloud solutions, where you can craft personalized and relevant experiences based on the user’s web behavior. 

To create a segment of visitors who have added products to their cart but not placed an order and then send it to the Experience Cloud:

1. Open the Segment Builder.
1. From the **Components** toolbar, scroll down to the **Segments** and click the plus icon to create a new segment. 
1. Name the segment and add criteria for Visits that abandon a cart.
1. Name your segment `Cart Abandonment Visits`.
1. Search for `Abandon Cart` in the **Components** search box. Adobe includes an **Abandon Cart** segment template for you to use as a starting point. These templates are identified by the folder-with-magnifying-glass icons. This template matches the need to show visits that added an item to their cart and then did not place an order.
1. Drag the component into the segment definition. It should appear like this:

*image here*

### Save segments and share them with Experience Cloud

To save the segment and share it with Experience Cloud:

1. Select the check box option under the segment definition. In the suggested look-back window, specify 90 days.
1. Click save. This shares an audience across Adobe Experience Cloud solutions. You can now use this to trigger emails in Campaign, show banner ads via Ad Cloud, or trigger a personalized offer the next time the visitor comes to your site via Target.

### Exclude fraud using virtual report suites

A Virtual Report Suite (VRS) is a view that is built from normal report suite data, with one or more segments permanently applied. They can be applied retroactively to past data, or you can update the segment to filter certain events in the past.

You can use a VRS to eliminate bot traffic that you did not previously catch, or to throw out online orders that were either fraudulent or had a currency conversion issue.

Consider setting up a VRS from initial implementation and using it continually, even if initially you are not filtering anything out. Then, if issues arise over time, you can add a segment to that VRS and you will not have to retrain others on switching report suites or finding segments/calculated metrics in a different suite.

### Integrate offline data using Data Import

Data Source import allows you to push offline data, such as cancelled orders and lead-to-revenue info, back to Adobe.

To get the most out of this feature, make sure to capture an online transaction ID at the time of the online conversion. Then, you can batch upload offline data referencing that same transaction ID and the new data associates with the online activity related to that transaction.

### Roll up/clean up dimension data using Classifications

You can import lookup tables of metadata (data about your data) to a dimension in Adobe Analytics. This is useful with Products. If your site tracks products by their SKU and the SKU 04852291147 is selling very well, you can upload a table translating that SKU into a product name, department, brand, or price point. Then you can pull a product name report, or a brand report.

This is a powerful and often underutilized feature, but do not be intimidated. If you can use a pivot table, you can grasp the concept quickly. Speak with your Analytics administrator to understand what you have available to you, since your implementation is highly customized to your business.

## Helpful Tips

This section provides instructions for some of the most useful and most common actions for working with Adobe Analytics.

## Saving and socializing your report

This section describes some standard options to store and distribute Analysis Workspace Projects.

### Save your project

On the Project menu, click **Save**. This saves the project in your account and you can come back to it whenever you would like. It is not shared with any other users unless you explicitly grant them access.

If you have not already named your project, you are prompted to do this upon saving.

### Share your report with other Adobe Analytics users

Under the **Share** menu in the light-grey header, you can share with individual users and user groups (if you have set groups up).  
  
### Point users directly to a specific report

To save other users from having to scroll through a list of projects, you can send users short links that drop users directly into a specific report. To generate a short link, click **Share** > **Get Project Link**. Use it and send it to others to make your report easy to find. 

### Download a report

Instead of taking screenshots, you can export your project as a PDF and send it to your recipient. Click **Project** > **Download PDF**.
  
### Email a report once or on a recurring basis

Click **Share** > **Send File Now** to email this to recipients. To email on a recurring basis, click **Send File On Schedule** Check to make sure that your date range is dynamic when you set recurring reports, otherwise you will receive the same date range every time it sends.  

### Manage shared reports

To manage reports that you are sharing with others (or that others are sharing with you), click **Components** > **Projects**. You can manage your dashboards, or Delete, Share, or Tag in Bulk.

## You are ready to switch

You now have a good understanding of how to replicate your most essential reporting in Adobe Analytics. Adobe is eager to hear your feedback and continue the conversation. 
