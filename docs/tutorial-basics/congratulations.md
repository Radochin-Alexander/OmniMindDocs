---
sidebar_position: 6
---

# Widgets

After the processor processes the provided information, the user is presented with a choice of Widget through which the interaction with OmniMind will be displayed.

## Types of widgets:

> **Search View** - A widget that provides a web search engine-like interface. The user enters a query in the input field or selects one of the suggested possible questions provided by the search engine. The user can also use filters to narrow down the results from the search engine sources. The OmniMind response includes links to the sources that had the highest match for the given query. The query history is displayed as a feed.

> **Chat View** - A widget that provides a messenger chat-like interface or a chat with support. The user enters a query in the input field or selects one of the suggested possible questions provided by the search engine. The OmniMind response includes links to the sources that had the highest match for the given query. The query history is displayed as a feed.

> **Explain View** - A widget that provides a single-answer interface, something between Chat View and Search View. The user enters a query in the input field or selects one of the suggested possible questions provided by the search engine. In this widget, the OmniMind response will not include links to sources, and each subsequent answer replaces the previous one.

> **API Basic Chains** - A widget that provides an interface through REST API. The user can perform any queries and run any chains. This is an advanced widget for developers.

### Widgets have additional options:

> **Share Widget** - An option that allows obtaining a link to a specific widget to interact with it, excluding the ability to edit the Project.

> **Resources** - An option that displays the resources involved in the Project (files, links, etc.) and allows adding and removing resources from the Project.

> **Widget Settings** - An option that allows configuring the specific widget.

It includes the following sub-items:

>> ***Embed Code:*** Provides the code for integration into the HTML structure, with the option to send the code via email.

>> ***Customize:*** Allows customization of the bot's logo (avatar), adds a caption for each bot response, allows setting a specific response for unknown questions, defines a special color scheme for the widget, and adjusts the font size in the widget.

>> ***ChatGPT:*** Allows configuring the type of neural network that will process the queries and adjust the creativity level of the responses.