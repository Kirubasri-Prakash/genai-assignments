S01 - DOM to Selenium Code-HW

java
import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.WebElement;
import org.openqa.selenium.chrome.ChromeDriver;

public class Main {
    public static void main(String[] args) {
        System.setProperty("webdriver.chrome.driver", "/path/to/chromedriver");
        WebDriver driver = new ChromeDriver();
        driver.get("your_website_url");

        WebElement companyNameInput = driver.findElement(By.name("companyName"));
        WebElement lastNameInput = driver.findElement(By.name("lastName"));
        WebElement firstNameInput = driver.findElement(By.name("firstName"));
        WebElement submitButton = driver.findElement(By.className("smallSubmit"));

        companyNameInput.sendKeys("Company Name");
        lastNameInput.sendKeys("Last Name");
        firstNameInput.sendKeys("First Name");
        submitButton.click();

        driver.quit();
    }
}

S02 - TextFromImage-Url-HW

मुड़ जाती हैं हाथों की लकीरें 
गर हिम्मत हैं तूफानों से लड़ने की 
होते होते पीछे ही हो जाते हैं 
बात जो करते हमेशा किस्मत की 

किस्मत में ही लिखा हो ऐसा, अगर 
हासिल होगा कुछ करते रहने से 
पूरे होंगे सारे सपने एक दिन, मगर 
वो दिन नहीं आता बैठे रहने से

S03-WebSearch-HW

Title: List of Chief Ministers of Tamilnadu From 1920 to 2026
URL: https://www.studyiq.com/articles/chief-ministers-of-tamilnadu/
Content: 1 week ago - Tamil Nadu has a rich political history, evolving from the Madras Presidency era (pre-independence) to a modern democratic state. As of 2026, M. K. Stalin is serving as the current Chief Minister of Tamil Nadu (since 2021).
Score: 1.0000

Title: Chief Ministers of Tamil Nadu (1952–2025): Current CM, First CM, Longest Serving & Full List
URL: https://www.pw.live/ssc/exams/chief-ministers-of-tamil-nadu
Content: Chief Ministers of Tamil Nadu: Tamil Nadu has seen several influential leaders since the formation of the state. The current Chief Minister of Tamil Nadu is M.K. Stalin , who has been serving since 7 May 2021.
Score: 0.9999

Title: Tamil Nadu Chief Minister M. K. Stalin said, 2026: We will return ...
URL: https://www.facebook.com/IndiaToday/posts/tamil-nadu-chief-minister-m-k-stalin-said-2026-we-will-return-bigger-and-betteri/1493251522838391/
Content: He added that he has taught the same to his son Deputy CM Udhayanidhi. He also shared his conviction that the DMK-led alliance will script a
Score: 0.9997

Title: List of Chief Ministers in Tamil Nadu - Complete & Updated Info
URL: https://www.bankbazaar.com/voter-id/chief-ministers-of-tamil-nadu.html
Content: Here is a list of the Chief Ministers of Tamil Nadu from its formation in 1969 to the present in 2025: ... The current Chief Minister of Tamil Nadu is M K Stalin .
Score: 0.9996

Title: Tamil Nadu Chief Minister MK Stalin filed his nomination ... - Facebook
URL: https://www.facebook.com/thehindu/videos/tamil-nadu-chief-minister-mk-stalin-filed-his-nomination-for-the-state-assembly-/939411012358853/
Content: Stalin filed his nomination for the State Assembly elections on Monday (March 30, 2026) from Kolathur in Chennai. The elections will take place
Score: 0.9994

Title: Who is the next CM in Tamil Nadu in 2026? - Quora
URL: https://www.quora.com/Who-is-the-next-CM-in-Tamil-Nadu-in-2026
Content: 2024 is not for Tamilnadu Legislative assembly where Tamilanadu Chief minister can be elected! but it is for Lok sabha election to elect
Score: 0.9986

Title: Chief Minister of Tamil Nadu - Wikipedia
URL: https://en.wikipedia.org/wiki/Chief_Minister_of_Tamil_Nadu
Content: The current incumbent is M. K. Stalin of the Dravida Munnetra Kazhagam since 7 May 2021.

## List

[edit]

The Madras Presidency, headquartered in Fort St. George, India, was a presidency of India that comprised present-day Tamil Nadu, the Malabar region "Malabar (Northern Kerala)") of North Kerala, the coastal and Rayalaseema regions of Andhra Pradesh, and the Bellary, Dakshina Kannada, and Udupi districts of Karnataka. It was established in 1653 to be the headquarters of the English settlements on the Coromandel Coast. [...] Since 1952, Tamil Nadu has had 12 chief ministers "Chief minister (India)"), 13 including V. R. Nedunchezhiyan, who twice acted in the role. The longest-serving chief minister, M. Karunanidhi from Dravida Munnetra Kazhagam, held the office for over eighteen years in multiple tenures, while he was the one who had the largest gap between two terms (nearly thirteen years). The All India Anna Dravida Munnetra Kazhagam's former general secretary J. Jayalalithaa has the second-longest tenure, and its founder M. G. Ramachandran, the first actor to become the chief minister in India, has the third-longest tenure, while his wife V. N. Janaki Ramachandran has the shortest tenure (only 23 days). There have been four instances of president's rule in Tamil Nadu, most recently in 1991. [...] | Elections |  1952  1957  1962  1967  1971  1977  1980  1984  1989  1991  1996  2001  2006  2011  2016  2021  2026 |
| Category |
Score: 0.9977

Title: T.N. Assembly | DMK will return to power, work with greater speed ...
URL: https://www.thehindu.com/news/national/tamil-nadu/tn-assembly-dmk-will-come-back-to-power-work-with-greater-speed-and-commitment-cm-stalin/article70655250.ece
Content: On the final sitting of the 16th Tamil Nadu Legislative Assembly on Friday (February 20, 2026), Chief Minister M.K. Stalin asserted that his
Score: 0.9961

Title: List of Chief Ministers of Tamil Nadu: 1920 – 2026 - JAIN PU Colleges
URL: https://www.jaincollege.ac.in/blogs/list-of-chief-ministers-of-tamil-nadu-1947-2025
Content: The Justice Party and Congress dominated early years, but the Dravidian movement (DMK and later AIADMK) has shaped the politics of Tamil Nadu
Score: 0.9951

Title: Chief ministership of M. K. Stalin - Wikipedia
URL: https://en.wikipedia.org/wiki/Chief_ministership_of_M._K._Stalin
Content: Muthuvel Karunanidhi Stalin has served as the 8th Chief Minister of Tamil Nadu since May 7, 2021. He is the leader of the Dravida Munnetra Kazhagam (DMK).
Score: 0.9943

Title: DMK Chief and Tamil Nadu CM MK Stalin holds door-to ... - YouTube
URL: https://www.youtube.com/watch?v=b0l6vs6W3jM
Content: తమిళనాడులో వినూత్నంగా స్టాలిన్ ఎన్నికల ప్రచారం! Tamil Nadu Assembly Polls 2026: DMK Chief and Tamil Nadu CM MK Stalin holds door-to-door Campaign | Zee Telugu
Score: 0.9927

Title: TVK Aadhav Arjun Declares Thalapathy Vijay as Tamil Nadu's Next ...
URL: https://www.youtube.com/watch?v=Y6k2rBJjazE
Content: In a bold political statement, TVK Aadhav Arjun predicts that popular actor Vijay will become Tamil Nadu's next Chief Minister.
Score: 0.9833

Title: M. K. Stalin - Wikipedia
URL: https://en.wikipedia.org/wiki/M._K._Stalin
Content: Muthuvel Karunanidhi Stalin (born 1 March 1953) is an Indian politician who has served as the eighth Chief Minister of Tamil Nadu since 2021. He became president of Dravida Munnetra Kazhagam (DMK) on 28 August 2018, after serving as the party's working president from January 2017 to August 2018. [...] | M. K. Stalin | |
 --- |
| Stalin in 2022 | |
|  | |
| 8th Chief Minister of Tamil Nadu | |
| Incumbent | |
| Assumed office  7 May 2021 | |
| Governor |  Banwarilal Purohit  R. N. Ravi  Rajendra Arlekar |
| Deputy | Udhayanidhi Stalin |
| Preceded by | Edappadi K. Palaniswami | [...] | 1st Deputy Chief Minister of Tamil Nadu | |
| In office 29 May 2009 – 15 May 2011 | |
| Governor | Surjit Singh Barnala |
| Chief Minister | M. Karunanidhi |
Score: 0.9827

Title: Vijay is set to become Tamil Nadu chief minister; party can form govt ...
URL: https://timesofindia.indiatimes.com/city/chennai/vijay-is-set-to-become-tamil-nadu-chief-minister-party-can-form-govt-in-puducherry-too-bussy-anand/articleshow/125872454.cms
Content: TVK general secretary (election campaign management) Aadhav Arjuna challenged Tamil Nadu chief minister M K Stalin to face the TVK in the
Score: 0.9807

Title: Tamil Nadu polls 2026: ECI transfers top officials, Stalin cries bias
URL: https://www.deccanherald.com/elections/tamil-nadu/tamil-nadu-assembly-elections-2026-chief-secretary-and-anti-corruption-wing-chief-transferred-cm-stalin-calls-it-partisan-move-3960984
Content: Sign in

DH Specials

Assembly Polls 2026

Bengaluru

Technology

Lifestyle

Trending

Photos

DH Brandspot

Menu

×

ADVERTISEMENT

ADVERTISEMENT

Homeelectionstamil nadu

# Tamil Nadu Assembly Elections 2026 | Chief Secretary and anti-corruption wing chief transferred, CM Stalin calls it ‘partisan move’

Sai Kumar, who is currently the Commissioner of Revenue Administration, will take charge immediately.

ETB Sivapriyan

Last Updated : 08 April 2026, 15:37IST

ADVERTISEMENT

Follow Us :

Comments

ADVERTISEMENT

Published 08 April 2026, 15:37IST

India NewsTamil NaduIndian PoliticsM K StalinTamil Nadu Assemblyassembly elections 2026

## Follow us on :

## Follow Us
Score: 0.9610

Title: Council of Ministers (TN) - Government of Tamil Nadu
URL: https://www.tn.gov.in/minister_list.php
Content: Thiru M.K.Stalin · Honourable Chief Minister · Thiru Duraimurugan · Honourable Minister for Water Resources · Thiru Udhayanidhi Stalin · Honourable Deputy Chief
Score: 0.9026

Title: List of Chief Ministers of Tamil Nadu | Tamil Nadu CMs List
URL: https://www.mapsofindia.com/tamilnadu/chief-ministers.html
Content: Find List of Tamil Nadu Chief Ministers state in India with their working tenure.
Score: 0.8344

S04- MultiLingual-HW

நன்றி! இந்த API-ஐ பயன்படுத்துவதற்கு, அதன் ஆவணங்களைப் படிக்கவும். அதில் உள்ள முறைகள் மற்றும் அவற்றின் பயன்பாடுகளைப் புரிந்துகொள்ளவும்.

பின்வரும் படிகளைப் பின்பற்றவும்:

1. **API கிளையன்ட் உருவாக்கவும்**: ஒரு கிளையன்ட் உருவாக்கவும், அதன் மூலம் நீங்கள் API சேவைகளை அணுகலாம்.
2. **API முறைகளை அழைக்கவும்**: நீங்கள் அணுக விரும்பும் API முறைகளை அடையாளம் கண்டு, அவற்றை அழைக்கவும்.
3. **தரவைச் செயலாக்கவும்**: நீங்கள் அழைத்த முறைகளிலிருந்து திரும்பப் பெறும் தரவைச் செயலாக்கவும்.
4. **பிழைகளைக் கையாளவும்**: ஏதேனும் பிழைகள் ஏற்பட்டால், அவற்றைக் கையாளவும் மற்றும் சரிசெய்யவும்.

இந்த API ஐ பயன்படுத்துவதற்கு உதவும் கோடுகள் மற்றும் எடுத்துக்காட்டுகளையும் நாங்கள் வழங்குகிறோம். அவற்றைப் பயன்படுத்தி, நீங்கள் தங்கள் சொந்த பயன்பாடுகளை உருவாக்கலாம்.

மேலும் உதவி தேவைப்பட்டால், எங்களுடன் தொடர்பு கொள்ளவும். நன்றி!

REST और RESTFUL दोनों ही वेब एप्लिकेशन और सेवाओं के डिज़ाइन और विकास से संबंधित हैं। यहाँ उनके बारे में विस्तार से जानकारी दी गई है:

**REST (Representational State of Resource)**

REST एक वास्तुकला शैली है जो वेब सेवाओं और एप्लिकेशनों के डिज़ाइन के लिए उपयोग की जाती है। यह एक व्यवस्थित तरीके से संसाधनों को प्रदर्शित करने और उनसे इंटरैक्ट करने के लिए एक ढांचा प्रदान करता है। REST के मुख्य सिद्धांत हैं:

1. **संसाधन-आधारित**: प्रत्येक संसाधन को एक विशिष्ट पहचानकर्ता (URI) द्वारा पहचाना जाता है।
2. **क्लाइंट-सर्वर विभाजन**: क्लाइंट और सर्वर अलग-अलग होते हैं, और वे एक दूसरे से स्वतंत्र रूप से विकसित किए जा सकते हैं।
3. **सर्वर की तरह**: सर्वर संसाधनों को प्रबंधित करता है और क्लाइंट को उनसे इंटरैक्ट करने के लिए अनुमति देता है।
4. **स्थिरता**: सर्वर द्वारा भेजे गए डेटा को क्लाइंट द्वारा संग्रहीत नहीं किया जाता है।
5. **परतें**: प्रणाली में कई परतें हो सकती हैं, जैसे कि प्रॉक्सी सर्वर और फायरवॉल।

**RESTFUL**

RESTFUL एक वेब सेवा है जो REST वास्तुकला शैली का पालन करती है। यह एक एप्लिकेशन प्रोग्रामिंग इंटरफ़ेस (API) है जो संसाधनों को प्रदर्शित करने और उनसे इंटरैक्ट करने के लिए उपयोग की जाती है। RESTFUL API के मुख्य सिद्धांत हैं:

1. **संसाधनों का प्रतिनिधित्व**: API संसाधनों को प्रदर्शित करने के लिए उपयोग की जाती है।
2. **HTTP विधियों का उपयोग**: API HTTP विधियों (जैसे कि GET, POST, PUT, DELETE) का उपयोग संसाधनों को प्रबंधित करने के लिए करती है।
3. **संसाधनों को पहचानने के लिए URI का उपयोग**: API संसाधनों को पहचानने के लिए URI का उपयोग करती है।

संक्षेप में, REST एक वास्तुकला शैली है जो वेब सेवाओं और एप्लिकेशनों के डिज़ाइन के लिए उपयोग की जाती है, जबकि RESTFUL एक वेब सेवा है जो REST वास्तुकला शैली का पालन करती है और संसाधनों को प्रदर्शित करने और उनसे इंटरैक्ट करने के लिए उपयोग की जाती है।