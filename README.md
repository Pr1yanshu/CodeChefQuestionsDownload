# CodeChefQuestionsDownload
Downloads questions from codechef as separate pdf files and organizes them into folders
Requires:
```
BeautifulSoup: pip install beautifulsoup4
mechanize: pip install mechanize
pdfkit :pip install pdfkit
pdfkit needs wkhtmltopdf to work .[Instructions] (https://pypi.python.org/pypi/pdfkit)
```
Replace 'school' in line 9 with 'school','easy' 'medium','hard' and 'challenge' for changing difficulty 
>difficulty= 'easy'

Run again if some error occurs. It wont replace pre-existing files and only download the ones that haven't been downloaded yet.
