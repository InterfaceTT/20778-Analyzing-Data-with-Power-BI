---
lab:
    title: 'DEMO - Using Marketplace Visualizations'
    module: 'Module 08 Demo - The Developer API Development with Power BI'
---
# Module 8: The Developer API Development with Power BI

- [Module 8: The Developer API Development with Power BI](#module-8-the-developer-api-development-with-power-bi)
  - [Lesson 1: The Power BI API](#lesson-1-the-power-bi-api)
  - [Lesson 2: Custom Visuals](#lesson-2-custom-visuals)
    - [Demo 1: Importing and Using a Custom Visual](#demo-1-importing-and-using-a-custom-visual)
      - [Import a Custom Visualization](#import-a-custom-visualization)
      - [Use a Custom Visualization](#use-a-custom-visualization)


## Lesson 1: The Power BI API 

### Demo 1: Using the Power BI Embedded Playground

1. In Internet Explorer, go to **https://microsoft.github.io/PowerBI-JavaScript/demo/v2-demo/index.html**.

1. Under **Sample Report**, click **Select**.

1. In the **Embed** pane, review the default options.

1. In the **Code** pane, review the code to embed the report, and then click **Run**.

1. In the **Log** pane, review the events listed, and then in the **Embedded view** pane, review the report.

1. In the **Region** section of the report, click **East**, and wait for the report to update showing on the results for the East region.

1. On the right-hand side of the report above **FILTERS**, click the expand arrow.

1. Expand **Month**, and then select **Jan-14**. Note that the report updates to show only data in the East region in January 2014.

1. Review the events list in the **Log** pane again.

1. In the **Interact** pane, expand **Data**, and then click **Export visual data summarized**.

1. In the **Code** pane, click **Run**.

1. Review the data returned to the **Log** pane.

1. In the left-hand menu, click **Sample tool**.

1. Under **Sample Q&A**, click **Select**.

1. In the **Embed** pane, review the default options.

1. In the **Code** pane, review the code to embed the Q&A element, and then click **Run**.

1. In the **Embedded view** pane, review the question and the answer.

1. Change the last variable in the question to **clustered bar chart**, and then review the change to the answer.

1. Close Internet Explorer.

---

## Lesson 2: Custom Visuals

### Demo 1: Importing and Using a Custom Visual

#### Import a Custom Visualization

1. In Internet Explorer, go to **https://app.powerbi.com/visuals**.

1. In the **Search Microsoft AppSource** box, type **Aster Plot**, and then press Enter.

1. In the **Aster Plot** visual, click **Get it now**.

1. In the **Sign in to Microsoft AppSource** dialog box, enter the credentials you used to sign up for Power BI service, and then click **Sign in**.

1. If the **One more thing** dialog box appears, click **Continue**.

1. On the **Office Store** page, click **Download for Power BI**.

1. In the message box, click **Save**, and download the visual to a folder on your local machine.

1. On the Taskbar, click **Power BI Desktop**.

1. In the **Welcome to** **Power BI Desktop** window, click **Already have a Power BI account? Sign in**.

1. In the **Sign in** dialog box, enter your account credentials, and then click **Sign in**.

1. In the **Sign in to your account** dialog box, enter your password credentials, and then click **Sign in**.

1. In the **Power BI Desktop** window, click **Open other reports**.

1. In the **Open** dialog box, browse to **D:\\Demofiles\\Mod08\\Demo**, click **Adventure Works Sales.pbix**, and then click **Open**.

1. If the **Introducing Q&A** dialog box appears, click **Got it**.

1. In the **VISUALIZATIONS** pane, click the ellipsis (**...**), and then click **Import from file**.

1. In the **Caution: Import custom visual** dialog box, click **Import**.

1. In the **Open** dialog box, browse to the location where you saved Aster Plot, click **AsterPlot.x.x.x.x.pbiviz**, and then click **Open**.

1. In the **Import custom visual** dialog box, click **OK**.

#### Use a Custom Visualization

1. In the **Report** view, at the bottom of the page, click the **Company Report** tab.

2. Click the **Line Total by Company Name** visual.

3. In the **Visualizations** pane, click the **Aster Plot** icon. Data that was previously displayed using the **Clustered column chart** is now displayed in the **Aster Plot** visualization.

4. Close Power BI Desktop, without saving any changes, and then close Internet Explorer.
