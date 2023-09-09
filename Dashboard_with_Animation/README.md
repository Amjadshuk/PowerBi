# Power BI Dashboard with (JS & CSS Content) README

Welcome to the Power BI Dashboard repository! This repository contains a Power BI dashboard project named "Dashboard_with_Animation.pbix" that includes animated visualizations and custom HTML content. To fully utilize this dashboard, please follow the steps outlined below, including the addition of the "ParaHTMLViewer" custom visual and base64 encoding of your HTML content.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The "Dashboard_with_Animation.pbix" Power BI Dashboard is designed to provide interactive visualizations and animations to help you analyze and present your data effectively. This README will guide you through the process of setting up and customizing the dashboard to meet your needs.

## Getting Started

To get started with this Power BI Dashboard, follow the steps outlined below:

## Requirements

Before using this dashboard, ensure you have the following prerequisites:

1. **Power BI Desktop**: You must have Power BI Desktop installed on your computer to open and edit this dashboard project. You can download Power BI Desktop from the official website: [Download Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).

2. **ParaHTMLViewer Custom Visual**: This dashboard uses the "ParaHTMLViewer" custom visual, which is not included in the default Power BI Desktop installation. You need to add this visual to your Power BI Desktop to make the dashboard work correctly.

## Installation

### Adding the "ParaHTMLViewer" Custom Visual:

1. Open Power BI Desktop.

2. Click on the "File" menu.

3. Select "Options and settings" > "Options."

4. In the Options window, navigate to "Security" on the left sidebar.

5. Under "Custom visuals," check the box that says "Allow any uncertified visuals to load."

6. Click the "OK" button to save your changes.

7. Now, you can add the "ParaHTMLViewer" custom visual to your report by following these steps:

   a. Click on the "Visualizations" pane on the right side of the Power BI Desktop window.

   b. Click on the ellipsis (...) to open the "Visualizations" menu.

   c. Choose "Import a custom visual."

   d. In the "Import a custom visual" dialog, select "Import from file."

   e. Locate and select the "ParaHTMLViewer" custom visual file (typically with a .pbiviz extension) that you have downloaded.

   f. Click "Open" to import the custom visual.

## Usage

Once you have installed the "ParaHTMLViewer" custom visual, you can customize the dashboard to your liking. The primary steps for adding custom HTML content and animations to your dashboard are as follows:

1. **Base64 Encoding HTML with CSS and JS Content**:
   Base64 encode your HTML content, including any embedded CSS and JavaScript, with the HTML base64 prefix URL. You can use online tools or libraries to accomplish this task.

2. **Add HTML Base64 String to Power BI Static Table**:
   Create a static table within your Power BI report and add a column to store the base64 encoded HTML strings. Make sure you have a column for each HTML element you want to display in the "ParaHTMLViewer" visual.

3. **Add HTML Content to the Template Field**:
   In the "ParaHTMLViewer" visual, use the template field to reference the HTML content from your static table. This will dynamically populate the visual with the encoded HTML content, enabling animations and custom HTML rendering.

## Contributing

If you would like to contribute to this project or report any issues, please feel free to create a pull request or submit an issue in the GitHub repository.

## License

This Power BI Dashboard is licensed under **none**. You are free to use, modify, and distribute this dashboard without any specific licensing restrictions.

Enjoy using your animated Power BI Dashboard! If you have any questions or need further assistance, please don't hesitate to reach out.
