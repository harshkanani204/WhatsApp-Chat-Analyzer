# WhatsApp Chat Analyzer

This is a Python-based tool for analyzing WhatsApp chat logs. With this tool, you can analyze a chat log exported from WhatsApp and get insights into the chat patterns, such as the most active users, popular words, and conversation topics.

## Features

The WhatsApp Chat Analyzer provides the following features:

- **Parsing**: Parses the exported WhatsApp chat log and extracts relevant information such as sender, timestamp, and message content.
- **Analytics**: Provides various analytics such as the most active users, popular words, and conversation topics.
- **Visualization**: Generates various plots such as a word cloud, bar chart, and line chart to visualize the results.

## Getting Started

### Prerequisites

To use this tool, you need to have Python 3 installed on your system.

### Installation

To install the WhatsApp Chat Analyzer, clone this repository to your local machine using:

```bash
git clone https://github.com/harshkanani204/WhatsApp-Chat-Analyzer.git
```

After cloning the repository, install the required Python libraries using:

```bash
pip install -r requirements.txt
```


### Usage

To use the WhatsApp Chat Analyzer, you need to export the chat log from WhatsApp and save it as a text file. To export the chat log, open the chat in WhatsApp, tap on the three dots on the top right corner, and select "More" > "Export chat". Choose whether to include media or not and select "Without Media" to export only the text messages.

Once you have the chat log saved as a text file, run the `app.py` script using the following command:

```bash
streamlit run app.py 
```

This will open into a browser where you can upload the chat log text file and view the analytics.

## Contributing

Contributions to this project are welcome! To contribute, please fork this repository, make your changes, and submit a pull request.

---