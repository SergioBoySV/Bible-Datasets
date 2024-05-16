# Bible-Datasets
This repository contains separate CSV files for each book in the Bible, with each file containing all the verses of that
book. Additionally, various versions of the Bible are included for comparison and analysis.

The directories containing Bible versions have the CSV files separated by Old and New Testament books for ease of access.
There is also a CSV file that contains the entire version, if that is what you need.

**CSV Format:**

`book_name,chapter_number,verse_number,verse_text`

---

## Overview
To collect this information, I scrape YouVersions' `Bible.com` using BeautifulSoup.

`Bible.com` uses unique book abbreviations and version ID's to serve the correct verses. See below:

`https://www.bible.com/bible/111/GEN.1.1`  
Leads to Genesis 1:1 NIV
 
`https://www.bible.com/bible/59/JHN.3.16`  
Leads to John 3:16 ESV 

**NOTE:**  
- The capitalization of the abbreviation in the link does not matter! For formatting purposes, I have camel cased them in the table below
- Links to verses will appear with the version acronym appended (eg, `https://www.bible.com/bible/59/JHN.3.16.ESV`) but including or excluding this does not affect link navigation.

### Books
| OT Books      | Abbreviation | | NT Books        | Abbreviation |
|---------------|--------------|-|-----------------|--------------|
| Genesis       | Gen          | | Matthew         | Mat          |
| Exodus        | Exo          | | Mark            | Mrk          |
| Levicticus    | Lev          | | Luke            | Luk          |
| Numbers       | Num          | | John            | Jhn          |
| Deuteronomy   | Deu          | | Acts            | Act          |
| Joshua        | Jos          | | Romans          | Rom          |
| Judges        | Jdg          | | 1 Corinthians   | 1Co          |
| Ruth          | Rut          | | 2 Corinthians   | 2Co          |
| 1 Samuel      | 1Sa          | | Galatians       | Gal          |
| 2 Samuel      | 2Sa          | | Ephesians       | Eph          |
| 1 Kings       | 1Ki          | | Philippians     | Php          |
| 2 Kings       | 2Ki          | | Colossians      | Col          |
| 1 Chronicles  | 1Ch          | | 1 Thessalonians | 1Th          |
| 2 Chronicles  | 2Ch          | | 2 Thessalonians | 2Th          |
| Ezra          | Ezr          | | 1 Timothy       | 1Ti          |
| Nehemiah      | Neh          | | 2 Timothy       | 2Ti          |
| Esther        | Est          | | Titus           | Tit          |
| Job           | Job          | | Philemon        | Phm          |
| Psalms        | Psa          | | Hebrews         | Heb          |
| Proverbs      | Pro          | | James           | Jas          |
| Ecclesiastes  | Ecc          | | 1 Peter         | 1Pe          |
| Song of Songs | Sng          | | 2 Peter         | 2Pe          |
| Isaiah        | Isa          | | 1 John          | 1Jn          |
| Jeremiah      | Jer          | | 2 John          | 2Jn          |
| Lamentations  | Lam          | | 3 John          | 3Jn          |
| Ezekiel       | Ezk          | | Jude            | Jud          |
| Daniel        | Dan          | | Revelation      | Rev          |
| Hosea         | Hos          | |                 |              | 
| Joel          | Jol          | |                 |              | 
| Amos          | Amo          | |                 |              | 
| Obadiah       | Oba          | |                 |              | 
| Jonah         | Jon          | |                 |              | 
| Micah         | Mic          | |                 |              | 
| Nahum         | Nam          | |                 |              | 
| Habakkuk      | Hab          | |                 |              | 
| Zephaniah     | Zep          | |                 |              | 
| Haggai        | Hag          | |                 |              | 
| Zechariah     | Zec          | |                 |              | 
| Malachi       | Mal          | |                 |              | 

### Versions
| Version | ID  |
|---------|-----|
| NIV     | 111 |
| ESV     | 59  |
| KJV     | 1   |
| NKJV    | 114 |
| NLT     | 116 |
| ASV     | 12  |
| MSG     | 97  |

These are just a couple versions. If you want to explore all versions available:
1. Navigate to `https://www.bible.com/versions`  
2. Click the version you're interested in
3. Inspect the link in your browser. There will be an integer denoting the ID for the version you want.
