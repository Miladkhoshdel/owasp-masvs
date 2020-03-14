# V1: نیازمندی های معماری، طراحی و مدلسازی تهدید

## هدف کنترل

در دنیای بی نقص، امنیت در تمام مراحل توسعه باید در نظر گرفته شود. اما در واقعیت، امنیت اغلب در مرحله آخر چرخه حیات توسعه نرم افزار مورد توجه است. علاوه بر کنترل های فنی، استاندارد وارسی امنیت برنامه کاربردی موبایل، نیاز به ایجاد فرایندهایی دارد که بتوان از مورد توجه قرار گرفتن امنیت در زمان برنامه ریزی معماری برنامه موبایل و  شناخت وظیفه مندی های اصلی و امنیتی مؤلفه ها  اطمینان حاصل نمود. از آنجایی که بسیاری از برنامه های موبایل به عنوان سرویس دهنده از راه دور عمل می کنند، باید از اعمال استانداردهای امنیتی مناسب برای آن سرویس ها اطمینان حاصل نمود - تست برنامه موبایل در محیط ایزوله کافی نیست.

دسته بندی "V1"، نیازمندی های مرتبط با فاز معماری و طراحی برنامه کاربردی موبایل را فهرست می نماید. به این ترتیب، این تنها دسته بندی است که به موارد آزمون فنی در راهنمای آزمودن برنامه کاربردی موبایل OWASP نگاشت نمی شود. برای پوشش موضوعاتی مانند مدلسازی تهدید، چرخه حیات توسعه امن نرم افزار، یا مدیریت کلید، خوانندگان MASVS باید با پروژه های مرتبط با OWASP و یا سایر استانداردهای ارائه شده در زیر مراجعه نمایند.

## نیازمندی های وارسی امنیتی

نیازمندی های سطح یک و دو استاندارد وارسی امنیت برنامه های کاربردی موبایل بصورت زیر فهرست شده اند.

| # | شناسه- آزمون امنیتی برنامه کاربردی موبایل | شرح |  سطح یک | سطح دو |
| -- | -------- | ---------------------- | - | - |
| **1.1** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -1 | تمامی مولفه های برنامه کاربردی مورد نیاز شناسایی و شناخته شده اند. | ✓ | ✓ |
| **1.2** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -2 | اعمال کنترل های امنیتی نه فقط در سمت مشتری بلکه در نقاط انتهایی از راه دور مرتبط نیز صورت می گیرد. | ✓ | ✓ |
| **1.3** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -3 | یک معماری سطح بالا در برنامه کاربردی موبایل و تمامی سرویس های متصل به آن تعریف شده است و امنیت در آن معماری در نظر گرفته شده است. | ✓ | ✓ |
| **1.4** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -4 | داده های حساس در برنامه کاربردی موبایل، به صراحت مشخص شده اند  | ✓ | ✓ |
| **1.5** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -5 | تمامی مولفه های برنامه کاربردی موبایل که فراهم کننده ی وظیفه مندی های امنیتی و تجاری هستند، مشخص  شده اند. |  | ✓ |
| **1.6** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -6 | مدلسازی تهدیدی که برای برنامه کاربردی موبایل و تمامی سرویس های مرتبط از راه دور ایجاد شده است، تهدیدات بالقوه و اقدامات متقابل را شناسایی می نماید. |  | ✓ |
| **1.7** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -7 | تمامی کنترل های امنیتی بصورت متمرکز پیاده سازی شده اند. |  | ✓ |
| **1.8** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -8 | یک خط مشی صریح برای نحوه مدیریت کلیدهای رمزنگاری (در صورت وجود) و چرخه عمر کلیدهای رمزنگاری اعمال می شود. در حالت ایده آل، از یک استاندارد مدیریت کلید همانند NIST SP 800-57 پیروی نمایید. |  | ✓ |
| **1.9** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -9 | یک مکانیزم برای اجرای بروز رسانی برنامه کاربردی موبایل وجود دارد. |  | ✓ |
| **1.10** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -10 | امنیت در تمامی مراحل چرخه حیات توسعه نرم افزار در نظر گرفته شده است. |  | ✓ |
| **1.11** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -11 | یک سیاست افشای مسئولیت پذیری (آسیب پذیری) در حال اجراست و به طور موثری اعمال می شود. |  | ✓ |
| **1.12** | آزمون امنیت برنامه کاربردی موبایل - فاز معماری -12 | برنامه کاربردی موبایل باید با قوانین و مقررات حفظ حریم خصوصی مطابقت داشته باشد. | ✓ | ✓ |

## مراجع

برای دریافت اطلاعات بیشتر به آدرس های زیر مراجعه نمایید:

- ده تهدید برتر موبایل OWASP -تهدید رتبه دهم (وظیفه مندی فرعی)- به آدرس - <https://owasp.org/www-project-mobile-top-10/2016-risks/m10-extraneous-functionality>
- راهنمای معماری امن OWASP به آدرس - <https://www.owasp.org/index.php/Application_Security_Architecture_Cheat_Sheet>
- مدلسازی تهدید OWASP  به آدرس - <https://www.owasp.org/index.php/Application_Threat_Modeling>
- راهنمای چرخه حیات توسعه امن نرم افزار OWASP  به آدرس - <https://www.owasp.org/index.php/Secure_SDLC_Cheat_Sheet>
- راهنمای چرخه حیات توسعه نرم افزار مایکروسافت - <https://www.microsoft.com/en-us/sdl/>
- استاندارد NIST SP 800-57  - <http://csrc.nist.gov/publications/nistpubs/800-57/sp800-57-Part1-revised2_Mar08-2007.pdf>
- security.txt - <https://securitytxt.org/>