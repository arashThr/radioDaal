![RadioDaal](https://raw.githubusercontent.com/behnum/radioDaal/master/public/img/radiodaal-en-logo.png)

<div dir="rtl">

# [رادیو دال]({{site.url}})
وب سایت رادیو دال، پادکست فارسی درباره تحصیل، کار و مهاجرت.

# درباره رادیو دال
مگه این نیست هرکدوم تا آخر عمر یه تعداد محدودی واژه میتونیم بگیم و بنویسیم و تایپ کنیم؟ پس بهتر نیست از این واژه ها به بهترین نحو ممکن استفاده کنیم و کلماتمون را تا جایی که میشه با افراد بیشتری به اشتراک بذاریم؟
رادیو دال هم با همین ایده شکل گرفته: من که میشستم با دوستام گپ بزنم و ازشون راجع به مهاجرت و کار و زندگی سوال بپرسم، خب چرا حرفها و تجربیاتشون رو با بقیه به اشتراک نذارم؟
به خصوص که وقتی میبینم خیلی‌ها واقعا، از جمله خود من نمی‌دونن که زندگی بعد از دانشگاه یا در محیط کار چه گزینه‌هایی پیش روشون میذاره.

# همیاری

## مصاحبه
اساس این پادکست بر مبنای مشارکت دوستان و به اشتراک گذاشتن تجربیاتی که داشتن با بقیه است. بنابراین اگر فکر می‌کنید انتخابی داشتید و مسیری رو طی کردین که در طول اون تجربه به درد بخوری به دست ‌آوردین خوشحال میشم باهام تماس بگیرید تا یه گپی خودمونی راجع بهش داشته باشیم. تمام اطلاعات لازم برای این کار رو [اینجا](https://radiodaal.ir/participate) می‌تونید مشاهده کنید.

## طراح
ممنون میشم اگر بین دوستان کسی هست که در زمینه طراحی مهارتی داره با من تماس بگیره تا بتونیم یه کم رنگ و لعاب بیشتری به پادکست اضافه کنیم.

# تماس
پیشنهادات، نظرات و سوالات خودتون رو می‌تونید از طریق [تلگرام](https://t.me/radioDaalBot) و یا [ایمیل](radioDaal@outlook.com) برای من بفرستید.

# مسائل فنی
این سایت یک سایت استاتیک هست. برای ساختش از جکیل استفاده شده و از طریق Netlify سرو میشه. راجع به چگونگی اتصال سایت به دامنه هم یکی از شنونده‌های پادکست مطلبی نوشته که در [اینجا](https://virgool.io/@dany_kh/githubpagesdominir-zqjgtpk5pjij) می‌تونید بخونید.

</div>

### Installation
```
brew upgrade ruby
brew link --overwrite ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
gem install --user-install bundler jekyll 
gem install jalalidate
gem install jekyll-paginate 
```

### Running
- Build: `jekyll build --watch`
- Serve: `jekyll serve --port 4000 --host 0.0.0.0 --incremental --watch`