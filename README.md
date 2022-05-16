# مولد الشهادات
اداة تسمح لك بتوليد شهادات كشهادات الكورسات، شهادات اتمام كورس معين، شهادة اتمام موضوع...الخ وبصورة سريعة جداً ، بجودة عالية.
هذا ليس كل شيء فهذه الاداة تولد لك الشهادات وبدون حد يذكر ، حيث يمكنك توليد اكثر من 500 شهادة بضغطة زر واحدة.
وهل هذا كل شيء؟ ؛) بالتأكيد كلا ليس كل شيء ، يمكنك الكتابة باللغات العربية والهندية والإنجليزية وغيرها :P
هل هذا كل شيء ؟! بالطبع لا، فهناك ميزة اضافية وهي ارسال الشهادات بصورة مباشرة لأيميلات الطلاب او المشاركين في دوراتك وندواتك
هي مفتوحة المصدر ويمكن التعديل عليها حسب الرغبة 
مكتوبة مع <3 بلغة بايثون 
# MyCertificates
Certificates Generator A tool that allows you to generate certificates such as course certificates, certificates of completing a specific course, certificate of completion of a topic ... etc. Very quickly, with high quality. 
This is not all, this tool generates certificates for you without a limit, where you can generate more than 500 certificates with the click of a button.
Is that all ?! Of course not, there is an additional advantage which is sending certificates directly to the emails of students or participants in your courses and seminars 
And is that all ? ;) its not all, you can write in arabic, hindi, english and more :P
It is open source and can be modified as desired.
Written with &lt;3 in Python.

# Required Libraries
<i> pip install arabic-reshaper </i><br/>
<i> pip install hashlib </i><br/>
<i> pip install qrcode </i><br/>
<i> pip install python-bidi </i><br/>
<i> pip install PIL </i><br/>
<i> pip install pandas </i><br/>
<i> pip install smtplib </i><br/>
<i> pip install imghdr </i><br/>


# How to use
<li>Imports all required libraries</li>
<li>Prepare the CSV file (which contains names & emails), <b><i>for arabic language please use any online tools to convert from xlsx to csv to support arabic</i></b></li>
<li>Prepare your certificate image and name it as <b><i>certificate.jpg</i></b> </li>
<li>Use the font <b><i>arial.ttf</i></b> that I've palced already in this repository , <i> or just simply use any font you wanted ;) </i> </li>
<li>Adjust the text position in <b> xy=(525,440) </b></li>
<li>If you are sending from <b>Gmail</b>, you will need to <a href='https://stackoverflow.com/questions/16512592/login-credentials-not-working-with-gmail-smtp' alt='stackoverflow'>check this link out</a> </li>
