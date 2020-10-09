# Changelog

## What's coming soon?

* Improvements to slice and section layouts
* Improvements to ingredient pills

## October 10, 2020

### 🎁 What's new?

* **Automagic color contrast** - Don't be afraid of the dark! **🎃**Now, when you change the background of your slices to a dark color, the slice will automatically invert its other colors so that it remains readable. It's a beautiful way to draw attention to the highlights of your data story! 

![Color your story with beautiful Sections.](.gitbook/assets/feature-inverting.gif)

* **Easier to find your way home** 🏠 ****- To get back to the apps page, just click the Apps button in the header of any app. It's a little like Little Red Riding Hood... but without the wolf.

### 🐛 Bug fixes & other improvements

* **Faster loading apps**: Apps built with uploaded CSVs now get faster the more you use them thanks to the magic of enhanced caching. Nobody likes waiting. Now there's less of it.
* **Better labels**: Ok, we know that in some situations, labeling in the [scatterplot chart](authoring-apps/story-designer/charts/scatterplot.md) was well... broken. 🤕It's better now. Boo-boo all gone. 
* **Bar charts use bucket order:** [Bar charts](authoring-apps/story-designer/charts/bar.md) that use [bucketed dimensions](authoring-apps/data-sources/advanced-ingredients/bucketed-dimensions.md) will now show the buckets in the order you defined them. After all, can't we all use a little more order?  
* **Map charts zoom out farther**: The [map chart](authoring-apps/story-designer/charts/map.md) now lets you zoom out farther to get a global perspective. 🌍Next step: Mars. Maybe
* Various performance and bug fixes. Much perform. Un-bugged.

## September 17, 2020

### 🎁 What's new?

* **An improved trend chart** 📈 - We did a brain upgrade on the trend chart. The [trend chart](authoring-apps/story-designer/charts/trend.md) is now smarter about handling dates and times. You can easily roll up dates by month or year \(see time ingredient improvement below\), see which dates are missing data, and select ranges of dates to filter the story below. Hey, Trend Chart: it's time you were schooled 🎓. 

![](.gitbook/assets/release-trend.gif)

* **Broken ingredients** 🐣- Change is hard, we know that. When you replace a CSV on a data source, sometimes the new data has different names or different data types. This can break data ingredients. You'll see these [broken ingredients](authoring-apps/data-sources/edit-a-data-source.md#fixing-broken-ingredients-caused-by-changes-in-column-names) highlighted \(in a style we call "the blushing zebra"\) so you can fix them. Now change isn't so hard. 

### 🐛 Bug fixes & other improvements

* **Roll up time ingredients by month or year**: You can easily roll up time ingredient dates by month or year by choosing a month or year format when [defining the time ingredient](authoring-apps/data-sources/adding-ingredients/#time-ingredient). It's time to roll ⏰.
* **New advanced ingredient functions:** There are new options for advanced aggregations. You can calculate [percentiles and ages](authoring-apps/data-sources/advanced-ingredients/advanced-formulas.md#aggregation-functions). This improvement is in the top percentile.
* **More docs on formatting:** The advanced ingredients docs now contains lots of examples of how to build [custom number formats](authoring-apps/data-sources/advanced-ingredients/advanced-formats.md#advanced-number-formats). `,.0f" days until Christmas"` might not mean anything to you, but it does to Juicebox. And to Santa. 🎁
* Various performance and bug fixes.

## August 27, 2020

### 🎁What's new? 

#### Share your app via a 🔗 link

Invite anyone to create an account and view your app by simply [sharing your access link](authoring-apps/publish-and-share/sharing-and-access-controls.md). ![](https://downloads.intercomcdn.com/i/o/239290807/d306c8ab532685085c8bbd63/feature-sharing2.gif)​

#### +New sign in with your existing account

[Sign in](viewing-apps/signing-in.md) or with Google, LinkedIn, or your email address.

 ​![](https://downloads.intercomcdn.com/i/o/239523099/6b98dbf90a20d77bea96a85d/feature-signin.gif)​

### 🐛Bug fixes & other improvements

* **A better new-app template** - Now, when you make a fresh new app, you'll get a nice template with a header, intro, and sections to fill in to make your data story even more envied by your coworkers.
* **Automagically add your data**🎩- When you add a Data Source to an app, press the "[Add Automagically](authoring-apps/data-sources/adding-ingredients/#adding-ingredients-automagically)" button to tell Juicebox which data columns you're most interested in.
* **Story designer slice card improvements** - Added emphasis to the "Save" button, added nice hovering touches, and cleaned some dusty corners.
* **No more "null island" ☠️🏝** - The map chart no longer displays Place dimension values where the latitude or longitude are missing \(null\) or are exactly 0,0 \(the location of what we affectionately call null island in the middle of the Atlantic Ocean. We're guessing that's not the location you really wanted 💀\).
* **Table slice column headers now resize** - The table chart no longer cuts off multi-line column headers. Instead, the column header will resize to fit. Nobody likes being squeezed into something that's too small.
* Various performance and bug fixes.

## August 6, 2020

### 🎁What's New?

* **Date improvements** 📅- New Data Ingredients options let you [group dates](authoring-apps/data-sources/advanced-ingredients/advanced-formulas.md#conversion-functions) by week, month, quarter or year.

### 🐛Bug Fixes & Other improvements

* Sharing is caring🔨- Lots of behind the scenes work to let you share your data stories.
* Juicebox is more outgoing and informative if there's an issue uploading data.
* Various infrastructure, error handling and warning improvements.

## July 16, 2020

### 🎁What's new?

* **Replace CSV** 🎉- Updating your data just got 💯better. Opening any existing CSV data source now gives you an option to replace its data.
* **Chat support** 🗣- Get quick access to docs and a place to ask your burning questions. Just click the "?" button in the top right to get started. 

### 🐛Bug fixes & other improvements

* Side panel measure formatting didn't work in some cases. We've ironed that out.
* Various data error handling and warning improvements.





