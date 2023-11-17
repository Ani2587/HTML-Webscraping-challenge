# data_collection

Follow the steps below to successfully run the code:
1. Clone the repository to your local machine.
2. My system is not recognizing the path of the chromedriver, causing the line "browser = Browser('chrome')" to fail in
   launching the Chrome browser. To address this issue, I have implemented the following workaround.
   This solution is expected to function seamlessly across all systems; however, if any issues arise, kindly consider commenting out these two lines of code
   
   executable_path = {'executable_path': ChromeDriverManager().install()}
   browser = Browser('chrome', **executable_path, headless=False)
   
   and uncommenting the line "browser = Browser('chrome')" in the code in both files part_1_mars_news.ipynb, part_2_mars_weather.ipynb.
   
4. The code will generate a "data" folder to store the output CSV file (scraped_data.csv).
   

