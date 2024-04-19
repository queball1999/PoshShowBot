# PoshShowBot 🤖
![th-2728423464](https://github.com/queball1999/PoshShowBot/assets/57122349/f75c22a2-9c8a-4206-892c-e85ea448a7ca)

Welcome to PoshShowBot! A seamless solution for running automated shows on PoshMark, enabling users to manage items with options for auctions or buy-now-only shows. PoshShowBot incorporates a user-friendly configuration to adjust show settings such as discounts and item order. Initially built as a Selenium IDE browser extension project, it is transitioning to a standalone Python/Selenium script for enhanced accessibility and functionality. Get ready to revolutionize your PoshMark shows with ease and efficiency.

## 📦 What's Inside?

PoshShowBot offers an easy-to-use interface that automates the management of PoshMark shows. This includes starting shows, managing item sequences, handling auctions, and applying predefined discounts for buy-now scenarios. Here’s why that’s important:

- **Automation Efficiency**: Automate the repetitive tasks of managing a show, allowing you to focus on sales and customer interaction.

- **Flexible Show Types**: Supports different types of shows, including auction-only and buy-now-only, tailored to your sales strategy.
  
- ** Customizable tags**: Supports defining up to 3 tags for each show.

- **Scalability**: Ready to handle any show size, from a few items to dozens, without losing performance.

- **Future-Proof**: Ongoing updates will include automated messages, improved listing sorting, and the ability to stream with music, enhancing the show experience. I also plan to either make this into a standalone Python script, or merge it into [PoshmarkNursery](https://github.com/xzhou13/PoshmarkNursery). Either way, I will keep the .side files intact and build a parser to those environments as well.

## 🚀 Quick Start

1. **Clone the Repository:**
   First things first, we want to clone the repository.

    ```bash
    git clone https://github.com/queball1999/PoshShowBot.git
    cd PoshShowBot
    ```

2. **Install Selenium IDE Browser Extension**
   Next, you need to install the Selenium IDE browser extension from your browser's extension store to run the .side project files. For Chrome, this can be found [here](https://chromewebstore.google.com/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd)
   
4. **Open .side file:**
   Open the Selenium IDE and import the .side file included in the repository. This file contains the automation scripts for your PoshMark shows.
   
6. **Configure and Launch PoshShowBot:**
   Configure the settings according to your show requirements, then use the Selenium IDE to run the script, automating tasks within your PoshMark show.

⚠ Warning ⚠: Be sure to sign into Poshmark in your browser. This will create the browser session needed for the bot. I hope to handle the sign-in process soon.

## 📖 Configuration
  Configuring PoshShowBot involves setting various parameters to tailor the bot to your specific needs. You can customize the following settings:

  Show Type: Choose between two pre-defined .side files based on the type of show you want to run — auction-only or buy-now-only. Each file is optimized for different selling strategies.
  Discount Percentage: Set the discount percentage for buy-now items to attract more buyers and increase sales during the show.
  Time Between Listings: Configure the time interval between listing items. This helps in managing the pace of the show and gives buyers enough time to engage with each listing.
  Number of Listings: Define the total number of listings to be managed during the show. This ensures that the bot operates within the scope of the show's intended size and duration.

## 🤝 Contributing
Contributions are welcome! Whether it's reporting issues, submitting improvements, or adding features, feel free to fork the repository and submit pull requests.

## 📝 License
This project is licensed under the GPL-3.0 license - see the LICENSE file for details.

## 🙏 Acknowledgments
Thanks to the creators of Selenium and the developers behind PoshMark for making this project possible.

## ⚠ Disclaimer
Disclaimer: This setup is intended for research and educational purposes only. Always ensure that your actions comply with PoshMark's terms and conditions.
