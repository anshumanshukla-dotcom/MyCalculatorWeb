# MyCalculatorWeb
*Working URL:* https://mycalculator.z13.web.core.windows.net/

## Synopsis
MyCalculator is an easy-to-use web application capable of performing simple and complex calculations as well. It is developed using HTML, CSS and JavaScript and is deployed on Microsoft's Azure.

## Deployment Steps Followed
I have deployed a static website (that is, MyCalculator) on Azure using Azure Storage accounts after logging into [Azure portal](https://portal.azure.com/).

- Firstly, I created a **Resource group**.
- Secondly, I created a **Storage account** with an unique name.
- After the deployment was successful I clicked on **Go to resource** and then moved on to **Static website**.
- I enabled the **Static website** option and typed the **Index document name**.
- After that I moved on to **Containers** and uploaded (using the interface) all the HTML, CSS and JavaScript files inside the **$web** container.
- Then I moved again to **Static website** section and copied the **Primary endpoint**.
- Lastly, I pasted the URL (copied from the previous step) to the browser.
