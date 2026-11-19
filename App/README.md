# پروژه آموزش تشبیه — ساخت APK با GitHub Actions

## نکته مهم هنگام بارگذاری در GitHub
محتویات این پوشه را مستقیماً در ریشه مخزن GitHub بارگذاری کنید؛ خود پوشهٔ `Amuzesh_Tashbih` را به‌صورت یک پوشهٔ تو در تو داخل مخزن قرار ندهید.

پس از بارگذاری، باید این مسیرها در صفحه اصلی مخزن دیده شوند:
- `.github/workflows/android.yml`
- `app/`
- `build.gradle.kts`
- `settings.gradle.kts`

## ساخت APK
1. همه فایل‌های این ZIP را در ریشه مخزن GitHub قرار دهید و Commit کنید.
2. وارد زبانهٔ **Actions** شوید.
3. گردش‌کار **Build Android APK** باید ظاهر شود. در صورت نیاز از دکمهٔ **Run workflow** آن را اجرا کنید.
4. پس از پایان موفق، وارد اجرای انجام‌شده شوید و از بخش **Artifacts** فایل `Amuzesh-Tashbih-debug-apk` را دریافت کنید.

فایل APK خروجی درون Artifact با نام `app-debug.apk` قرار می‌گیرد.
