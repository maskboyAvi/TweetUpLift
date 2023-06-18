# TweetUpLift
Chrome extension to analyze and perform sentiment analysis of  your twitter profile and give points accordingly.
![Screenshot (154)](https://github.com/maskboyAvi/TweetUpLift/assets/123640350/dbe9122e-e026-481f-9679-e2685cd20824)

# Twitter Sentiment Analyzer Chrome Extension

This Chrome extension allows users to analyze and perform sentiment analysis of their Twitter profile. It provides points based on the sentiment of the user's tweets, which can be used to assess their mental health. The extension integrates with the Twitter API to fetch the user's tweets and uses a sentiment analysis algorithm to determine the sentiment of each tweet.

## Features

- Analyze the sentiment of a user's Twitter profile.
- Assign points to the user based on the sentiment of their tweets.
- Provide an overall mental health assessment based on the accumulated points.

## Prerequisites

Before using the extension, you need to have the following:

- Google Chrome browser installed on your computer.
- A Twitter Developer Account to access the Twitter API. You can create an account and set up an application at the [Twitter Developer Portal](https://developer.twitter.com/).

## Installation

To install the Twitter Sentiment Analyzer Chrome Extension, follow these steps:

1. Clone the repository:
   ```bash
   git clone (https://github.com/maskboyAvi/TweetUpLift)
   ```

2. Open Google Chrome and navigate to `chrome://extensions`.

3. Enable "Developer mode" by toggling the switch at the top right corner of the page.

4. Click on the "Load unpacked" button.

5. Select the cloned repository folder (`twitter-sentiment-analyzer`) and click "Open".

6. The extension should now be added to Chrome, and you should see its icon in the toolbar.

## Configuration

To configure the extension and set up your Twitter API credentials, follow these steps:

1. Open the extension by clicking on its icon in the toolbar.

2. Click on the "Settings" button.

3. Enter your Twitter API credentials:
   - Consumer Key
   - Consumer Secret
   - Access Token
   - Access Token Secret

4. Click "Save" to store the credentials.

## Usage

To analyze your Twitter profile and assess your mental health, follow these steps:

1. Make sure you are logged into your Twitter account in the browser.

2. Click on the extension icon in the toolbar.

3. Click on the "Analyze Profile" button.

4. The extension will fetch your tweets and perform sentiment analysis.

5. Once the analysis is complete, the extension will assign points to each tweet based on sentiment and calculate an overall mental health score.

6. The mental health score will be displayed along with a summary of the analysis.

## Contributing

Contributions to this project are welcome. To contribute, follow these steps:

1. Fork the repository.

2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:
   ```bash
   git commit -m "Add your commit message"
   ```

4. Push your changes to the forked repository:
   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request on the original repository and describe your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The sentiment analysis algorithm used in this extension is [Linear Regression]
- This extension utilizes the [Twitter API](https://developer.twitter.com/).

Feel free to customize and enhance the extension to suit your needs. If you have any questions or encounter any issues, please submit them to the GitHub repository's issue tracker.
