**Test Case**

**1.Test case ID:**TC_001

**2.Test Case Title:** Doğru məlumatlarla istifadəçi qeydiyyatı

**3.Preconditions:**

İstifadəçi qeydiyyatdan keçməmişdir

Qeydiyyat(Sign Up) səhifəsi açıqdır

**4.Test Steps:**

1.  Registr səhifəsinə keç

2.  Ad daxil et

3.  Soyad daxil et

4.  Email daxil et

5.  Şifrə daxil et

6.  Doğum tarixi daxil et

7.  Cinsiyyət seç

8.  Sign Up düyməsinə klik et

**5.Expected Result:**

İstifadəçi uğurla qeydiyyatdan keçir

Login səhifəsinə yönləndirilir

**6.Actual Result:**

İstifadəçi qeydiyyatı tamamladı

**7.Status:**

Passed

**1.Test case ID:** TC_002

**2.Test Case Title:** Yalnış email ilə qeydiyyat

**3.Preconditions:**

İstifadəçi qeydiyyatdan keçməmişdir

Qeydiyyat(Sign Up) səhifəsi açıqdır

**4.Test Steps:**

1.  Registr səhifəsinə keç

2.  Ad daxil et

3.  Soyad daxil et

4.  Yanlış email daxil et

5.  Şifrə daxil et

6.  Sign up düyməsinə klik et

**5.Expected Result:**

İstifadəçi qeydiyyatdan keçə bilmir

Email üçün xəta mesajı göstərilir

**6.Actual Result:**

Error mesajı göstərildi və qeydiyyat uğursuz oldu

**7.Status:**

Passed

**1.Test case ID:**TC_003

**2.Test Case Title:** Boş məlumatlarla istifadəçi qeydiyyatı

**3.Preconditions:**

İstifadəçi qeydiyyatdan keçməmişdir

Qeydiyyat(Sign Up) səhifəsi açıqdır

**4.Test Steps:**

1.  Registr səhifəsinə keç

2.  Ad daxil et

3.  Soyad daxil et

4.  Email sahəsini boş burax

5.  Şifrə sahəsini boş burax

6.  Sign up düyməsinə klik et

**5.Expected Result:**

Email və şifrə sahələri boş olduqda validation mesajları göstərilir

İstifadəçi qeydiyyatdan keçə bilmir

**6.Actual Result:**

Validation mesajları göstərildi və qeydiyyat baş tutmadı

**7.Status:**

Passed

**1.Test case ID:** TC_004

**2.Test Case Title:** Istifadə olunmuş email ilə qeydiyyat

**3.Preconditions:**

İstifadəçi qeydiyyatdan keçməmişdir

Qeydiyyat(Sign Up) səhifəsi açıqdır

**4.Test Steps:**

1.  Registr səhifəsinə keç

2.  Ad daxil et

3.  Soyad daxil et

4.  İstifadə olunmuş email daxil et

5.  Sign up düyməsinə klik et

**5.Expected Result:**

Daxil edilən email artıq istifadə olunubsa uyğun xəta mesajı göstərilir

İstifadəçi qeydiyyatdan keçə bilmir

**6.Actual Result:**

Validation mesajı göstərilir və qeydiyyat baş tutmur

**7.Status:**

Passed

**Test Case ID:** TC_005

**Test Case Title:** Şifrə və təkrar şifrə uyğun deyil

**Preconditions:**

Register səhifəsi açıqdır

**Test Steps:**

1.Register səhifəsinə keç

2.Şifrə daxil et

3.Fərqli təkrar şifrə daxil et

4.Digər sahələri doldur

5.Sign Up düyməsinə klik et

**Expected Result:**

"Şifrələr uyğun deyil" mesajı göstərilir

Qeydiyyat baş tutmur

**Actual Result:**

Error mesajı göstərildi və qeydiyyat baş tutmadı

**Status:**

Passed

**Test Case ID:** TC_006

**Test Case Title:** Məcburi sahələr doldurulmadan qeydiyyat

**Preconditions:**

Register səhifəsi açıqdır

**Test Steps:**

1.Register səhifəsinə keç

2.Bəzi sahələri boş burax

3.Sign Up düyməsinə klik et

**Expected Result:**

Məcburi sahələr üçün validation mesajı göstərilir

Qeydiyyat baş tutmur

**Actual Result:**

Validation mesajları göstərildi və qeydiyyat baş tutmadı

**Status:**

Passed

**Test Case ID:** TC_007

**Test Case Title:** Ad sahəsinə rəqəm daxil edilməsi

**Preconditions:**

Register səhifəsi açıqdır

**Test Steps:**

1.Register səhifəsinə keç

2.Ad sahəsinə rəqəm daxil et (məs: 1234)

3.Digər sahələri düzgün doldur

4.Sign Up düyməsinə klik et

**Expected Result:**

Ad sahəsi üçün xəta mesajı göstərilir

Qeydiyyat baş tutmur

**Actual Result:**

Validation mesajı göstərildi və qeydiyyat baş tutmadı

**Status:**

Passed

**Test Case ID:** TC_008

**Test Case Title:** Şifrə minimum uzunluqdan qısa daxil edilməsi

**Preconditions:**

Register səhifəsi açıqdır

**Test Steps:**

1.Register səhifəsinə keç

2.Digər sahələri doldur

3.Qısa şifrə daxil et (məs: 123)

4.Sign Up düyməsinə klik et

**Expected Result:**

Şifrə çox qısadır mesajı göstərilir

Qeydiyyat baş tutmur

**Actual Result:**

Validation mesajı göstərildi və qeydiyyat baş tutmadı

**Status:**

Passed

**Test Case ID:** TC_009

**Test Case Title:** Email sahəsinə böyük hərflərlə daxil edilməsi

**Preconditions:**

Register səhifəsi açıqdır

**Test Steps:**

1.Register səhifəsinə keç

2.Email sahəsinə böyük hərflərlə email daxil et (məs:

TEST@MAIL.COM)

3.Digər sahələri doldur

4.Sign Up düyməsinə klik et

**Expected Result:**

Sistem emaili qəbul edir

Qeydiyyat uğurla baş tutur

**Actual Result:**

Qeydiyyat uğurla tamamlandı

**Status:**

Passed

**1.Test case ID:**TC_010

**2.Test Case Title:** Doğru məlumatlarla istifadəçi girişi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**4.Test Steps:**

1.  Login səhifəsinə keç

2.  Doğru email daxil et

3.  Doğru şifrə daxil et

4.  Login düyməsinə klik et

5.  

**5.Expected Result:**

Istifadəçi uğurla daxil olur və ana səhifəyə yönləndirilir

**6.Actual Result:**

Istifadəçi uğurla daxil oldu və ana səhifəyə yönləndirildi

**7.Status:**

Passed

**1.Test case ID:**TC_011

**2.Test Case Title:** Yanlış məlumatlarla istifadəçi girişi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**4.Test Steps:**

1.  Login səhifəsinə keç

2.  Yanlış email daxil et

3.  Yanlış şifrə daxil et

4.  Login düyməsinə klik et

**5.Expected Result:**

İstifadəçi daxil ola bilmir

Xəta mesajı göstərilir

**6.Actual Result:**

Error mesajı göstərildi və istifadəçi daxil ola bilmədi

**7.Status:**

Passed

**1.Test case ID:**TC_012

**2.Test Case Title:** Boş məlumatlarla istifadəçi girişi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**4.Test Steps:**

1.  Login səhifəsinə keç

2.  Email sahəsini boş burax

3.  Şifrə sahəsini boş burax

4.  Login düyməsinə klik et

**5.Expected Result:**

İstifadəçi daxil ola bilmir

Email və şifrə sahələri üçün validation mesajları göstərilir

**6.Actual Result:**

Error mesajı göstərildi və istifadəçi daxil ola bilmədi

**7.Status:**

Passed

**1.Test case ID:**TC_013

**2.Test Case Title:** Qeydiyyatda olmayan email ilə istifadəçi girişi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**4.Test Steps:**

1.  Login səhifəsinə keç

2.  Qeydiyyatda olmayan email daxil et

3.  Doğru şifrə daxil et

4.  Login düyməsinə klik et

**5.Expected Result:**

İstifadəçi daxil ola bilmir

"User not found" və ya uyğun xəta mesajı göstərilir

**6.Actual Result:**

Error mesajı göstərildi və istifadəçi daxil ola bilmədi

**7.Status:**

Passed

**Test Case ID:** TC_014

**Test Case Title:** Login zamanı "Enter" düyməsi ilə daxil olma

**Preconditions:**

Login səhifəsi açıqdır

**Test Steps:**

1.Login səhifəsinə keç

2.Email daxil et

3.Şifrə daxil et

4.Klaviaturada "Enter" düyməsinə bas

**Expected Result:**

İstifadəçi uğurla daxil olur

**Actual Result:**

İstifadəçi uğurla daxil oldu

**Status:**

Passed

**Test Case ID:** TC_015

**Test Case Title:** Şifrəni göstər/gizlət funksiyası

**Preconditions:**

Login səhifəsi açıqdır

**Test Steps:**

1.Login səhifəsinə keç

2.Şifrə daxil et

3."Show/Hide password" ikonuna klik et

**Expected Result:**

Şifrə göstərilir və ya gizlədilir

**Actual Result:**

Şifrə uğurla göstərildi və gizlədildi

**Status:**

Passed

**Test Case ID:** TC_016

**Test Case Title:** Email sahəsinə boşluq + mətn daxil edilməsi

**Preconditions:**

Login səhifəsi açıqdır

**Test Steps:**

1.Login səhifəsinə keç

2.Email sahəsinə əvvəl boşluq sonra email daxil et (məs: ␣test@mail.com)

3.Şifrə daxil et

4.Login düyməsinə klik et

**Expected Result:**

Sistem boşluqları ignore edir və düzgün login olur

**Actual Result:**

İstifadəçi uğurla daxil oldu

**Status:**

Passed

**Test Case ID:** TC_017

**Test Case Title:** Login düyməsinə çox dəfə klik edilməsi

**Preconditions:**

Login səhifəsi açıqdır

**Test Steps:**

1.  Login səhifəsinə keç

2.  Email və şifrə daxil et

3.  Login düyməsinə bir neçə dəfə ardıcıl klik et

**Expected Result:**

Sistem yalnız bir dəfə login edir

Təkrar sorğular yaranmır

**Actual Result:**

Sistem bir dəfə login etdi və problem olmadı

**Status:**

Passed

**1.Test case ID:**TC_018

**2.Test Case Title:** Yanlış formatda email ilə giriş

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**4.Test Steps:**

1.  Login səhifəsinə keç

2.  Simvollardan ibarət(\*?%.) email daxil et

3.  Doğru şifrə daxil et

4.  Login düyməsinə klik et

**5.Expected Result:**

İstifadəçi daxil ola bilmir

Xəta mesajı göstərilir

**6.Actual Result:**

Error mesajı çıxdı və login olmadı

**7.Status:**

Passed

**Test Case ID:** TC_019

**Test Case Title:** Çox uzun email ilə giriş

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**Test Steps:**

1.  Login səhifəsinə keç

2.  Çox uzun email daxil et

3.  Şifrə daxil et

4.  Login düyməsinə klik et

**Expected Result:**

Sistem email uzunluğunu qəbul etmir

Xəta mesajı göstərilir

**Actual Result:**

Error mesajı göstərildi və giriş baş tutmadı

**Status:**Passed

**Test Case ID:** TC_020

**Test Case Title:** Email sahəsinə boşluq (space) daxil edilməsi

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

Login səhifəsi açıqdır

**Test Steps:**

1.  Login səhifəsinə keç

2.  Email sahəsinə yalnız boşluq daxil et

3.  Şifrə daxil et

4.  Login düyməsinə klik et

**Expected Result:**

Validation mesajı göstərilir

Giriş baş tutmur

**Actual Result:**

Validation mesajı göstərildi və giriş baş tutmadı

**Status:**

Passed

**1.Test case ID:** TC_021

**2.Test Case Title:** Məhsul axtarışı

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Axtarış (Search) sahəsinə klik et

3.  Məhsul adını daxil et

4.  Axtarış düyməsinə klik et (əgər varsa)

**5.Expected Result:**

Axtarışa daxil edilən məhsul nəticələrdə göstərilir

**6.Actual Result:**

Axtarılan məhsul nəticələrdə göstərildi

**7.Status:**

Passed

**1.Test case ID:** TC_022

**2.Test Case Title:** Mövcud olmayan məhsul axtarışı

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Axtarış (Search) sahəsinə klik et

3.  Məhsul adını daxil et

4.  Axtarış düyməsinə klik et

**5.Expected Result:**

Axtarış nəticəsi tapılmadıqda uyğun mesaj göstərilir

**6.Actual Result:**

Məhsul stokda olmadığına dair uyğun mesajı göstərildi

**7.Status:**

Passed

**1.Test case ID:** TC_023

**2.Test Case Title:** Stokda olmayan məhsul üçün oxşar məhsulların
göstərilməsi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Axtarış (Search) sahəsinə klik et

3.  Məhsul adını daxil et

4.  Axtarış düyməsinə klik et

**5.Expected Result:**

Məhsul stokda olmadığı barədə mesaj göstərilir

Oxşar məhsullar istifadəçiyə təklif edilir

**6.Actual Result:**

Məhsul stokda olmadığı mesajı göstərildi

Oxşar məhsullar ekranda göstərildi

**7.Status:**

Passed

**Test Case ID:** TC_024

**Test Case Title:** Eyni məhsulun təkrar axtarışı

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Məhsul adı daxil et və axtar

3.  Eyni məhsulu yenidən axtar

**Expected Result:**

Eyni nəticələr göstərilir

**Actual Result:**

Eyni məhsul nəticələrdə göstərildi

**Status:**

Passed

**Test Case ID:** TC_025

**Test Case Title:** Çox uzun mətn ilə axtarış

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Uzun və mənasız mətn daxil et

3.  Axtarış et

**Expected Result:**

Nəticə tapılmır və ya uyğun mesaj göstərilir

**Actual Result:**

Nəticə tapılmadı və mesaj göstərildi

**Status:**

Passed

**Test Case ID:** TC_026

**Test Case Title:** Böyük və kiçik hərflərlə axtarış

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Məhsul adını kiçik hərflərlə yaz və axtar

3.  Eyni məhsulu böyük hərflərlə yaz və axtar

**Expected Result:**

Hər iki halda eyni nəticələr göstərilir

**Actual Result:**

Eyni məhsul hər iki halda göstərildi

**Status:**

Passed

**Test Case ID:** TC_027

**Test Case Title:** Axtarış nəticəsində birdən çox məhsulun
göstərilməsi

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Ümumi məhsul adı daxil et

3.  Axtarış et

**Expected Result:**

Uyğun bir neçə məhsul nəticələrdə göstərilir

**Actual Result:**

Bir neçə uyğun məhsul göstərildi

**Status:**

Passed

**Test Case ID:** TC_028

**Test Case Title:** Axtarış sahəsinə boşluq + mətn daxil edilməsi

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Məhsul adından əvvəl boşluq daxil et

3.  Axtarış et

**Expected Result:**

Sistem boşluğu nəzərə almır və düzgün nəticə göstərir

**Actual Result:**

Məhsul düzgün şəkildə göstərildi

**Status:**

Passed

**Test Case ID:** TC_029

**Test Case Title:** Axtarış nəticələrinin sıralanması

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Məhsul adı daxil et

3.  Axtarış et

4.  Sıralama (Sort) seçimini dəyiş (məs: qiymətə görə)

**Expected Result:**

Məhsullar seçilmiş sıralamaya uyğun düzülür

**Actual Result:**

Məhsullar düzgün şəkildə sıralandı

**Status:**

Passed

**Test Case ID:** TC_030

**Test Case Title:** Axtarış nəticəsində məhsula klik etmə

**Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**Test Steps:**

1.  Axtarış sahəsinə klik et

2.  Məhsul adı daxil et

3.  Axtarış et

4.  Nəticələrdən birinə klik et

**Expected Result:**

Məhsulun detallı səhifəsi açılır

**Actual Result:**

Məhsul səhifəsi uğurla açıldı

**Status:**

Passed

**1.Test case ID:** TC_031

**2.Test Case Title:** Kateqoriyaya görə məhsulların göstərilməsi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Kateqoriya bölməsinə keç

3.  Hər hansı bir kateqoriyanı seç

**5.Expected Result:**

Seçilmiş kateqoriyaya aid məhsullar ekranda göstərilir

**6.Actual Result:**

Seçilmiş kateqoriyaya aid məhsullar ekranda göstərilir

**7.Status:**

Passed

**1.Test case ID:** TC_032

**2.Test Case Title:** Kateqoriya dəyişdikdə məhsulların yenilənməsi

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Kateqoriya bölməsinə keç

3.  Fərqli bir kateqoriya seç

**5.Expected Result:**

Fərqli kateqoriya seçilən zaman məhsul siyahısı yenilənir və seçilmiş
kateqoriya uyğun məhsullar göstərilir

**6.Actual Result:**

Fərqli kateqoriya seçilən zaman məhsul siyahısı yenilənir və seçilmiş
kateqoriya uyğun məhsullar göstərildi

**7.Status:**

Passed

**1.Test case ID:** TC_033

**2.Test Case Title:** Kateqoriya ilə filtr birlikdə

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Kateqoriya bölməsinə keç

3.  Hər hansı bir kateqoriyanı seç

4.  Filter tətbiq et

**5.Expected Result:**

Seçilmiş kateqoriya və tətbiq edilmiş filtrə uyğun məhsullar göstərilir

**6.Actual Result:**

Seçilmiş kateqoriya və tətbiq edilmiş filtrə uyğun məhsullar göstərilir

**7.Status:**

Passed

**1.Test case ID:** TC_034

**2.Test Case Title:** Seçilən kateqoriya bölməsində çox məhsul olması

**3.Preconditions:**

İstifadəçi artıq qeydiyyatdan keçib

İstifadəçi login olub və ana səhifədədir

Seçilmiş kateqoriyada çox sayda məhsul mövcuddur

**4.Test Steps:**

1.  Ana səhifəyə keç

2.  Kateqoriya bölməsinə keç

3.  Hər hansı bir kateqoriyanı seç

4.  Aşağıda hissədə "Next" düyməsinə yaxud ox işarələrinə klik et

**5.Expected Result:**

"Next" düyməsinə klik edildikdə növbəti səhifə açılır və yeni məhsullar
göstərilir

**6.Actual Result:**

"Next" düyməsinə klik edildikdə növbəti səhifəyə keçid baş vermədi

**7.Status:**

Failed

**Test Case ID:** TC_035

**Test Case Title:** Eyni kateqoriyanı təkrar seçmək

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

2.  Hər hansı kateqoriyanı seç

3.  Eyn kateqoriyanı yenidən seç

**Expected Result:**

Sistem stabil qalır və məhsullar dəyişmir

**Actual Result:**

Sistem stabil qaldı və məhsullar dəyişmədi

**Status:**

Passed

**Test Case ID:** TC_036

**Test Case Title:** Kateqoriya yüklənmədikdə davranış

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

**Expected Result:**

Yüklənmə (loading) və ya error mesajı göstərilir

**Actual Result:**

Loading göstərildi və sonra səhifə açıldı

**Status:**

Passed

**Test Case ID:** TC_037

**Test Case Title:** Kateqoriya seçildikdə məhsul siyahısının boş
gəlməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

2.  Məhsul olan kateqoriyanı seç

**Expected Result:**

Seçilmiş kateqoriyaya uyğun məhsullar göstərilməlidir

**Actual Result:**

Məhsul siyahısı boş göstərildi

**Status:**

Failed

**Test Case ID:** TC_038

**Test Case Title:** Kateqoriya seçimi zamanı səhv kateqoriyanın
açılması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

2.  Bir kateqoriyanı seç

**Expected Result:**

Seçilmiş kateqoriyaya uyğun məhsullar göstərilir

**Actual Result:**

Fərqli kateqoriyaya aid məhsullar göstərildi

**Status:**

Failed

**Test Case ID:** TC_039

**Test Case Title:** Kateqoriya seçildikdən sonra geri qayıtma

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

2.  Hər hansı kateqoriyanı seç

3.  Geri (back) düyməsinə klik et

**Expected Result:**

İstifadəçi əvvəlki səhifəyə qayıdır

**Actual Result:**

İstifadəçi əvvəlki səhifəyə qayıtdı

**Status:**

Passed

**Test Case ID:** TC_040

**Test Case Title:** Kateqoriya seçimi zamanı çox sürətli klik etmə

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Kateqoriya bölməsinə keç

2.  Bir neçə kateqoriyanı ardıcıl sürətli klik et

**Expected Result:**

Sistem stabil işləyir və səhv baş vermir

**Actual Result:**

Sistem stabil qaldı və düzgün işləməyə davam etdi

**Status:**

Passed

**Test Case ID:** TC_041

**Test Case Title:** Qiymətə görə filtr tətbiqi

**Preconditions:**

İstifadəçi login olub

Məhsul siyahısı səhifəsi açıqdır

**Test Steps:**

1.  Məhsul siyahısına keç

2.  Qiymət filterini seç (0--50 AZN)

3.  Filtri tətbiq et

**Expected Result:**

Seçilmiş qiymət aralığına uyğun məhsullar göstərilir

**Actual Result:**

Uyğun məhsullar göstərildi

**Status:**

Passed

**Test Case ID:** TC_042

**Test Case Title:** Kateqoriya üzrə filtr tətbiqi

**Preconditions:**

İstifadəçi login olub

Filter bölməsi mövcuddur

**Test Steps:**

1.  Filter bölməsinə keç

2.  Kateqoriya seç

3.  Filtri tətbiq et

**Expected Result:**

Seçilmiş kateqoriyaya uyğun məhsullar göstərilir

**Actual Result:**

Uyğun məhsullar göstərildi

**Status:**

Passed

**Test Case ID:** TC_043

**Test Case Title**: Birdən çox filtrin birlikdə tətbiqi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Qiymət filteri seç

2.  Kateqoriya filteri seç

3.  Filtri tətbiq et

**Expected Result:**

Hər iki filterə uyğun məhsullar göstərilir

**Actual Result:**

Uyğun məhsullar göstərildi

**Status**:

Passed

**Test Case ID:** TC_044

**Test Case Title:** Filtri sıfırlama (reset)

**Preconditions:**

İstifadəçi login olub

Ən azı bir filter aktivdir

**Test Steps:**

1.  Filtri tətbiq et

2.  Reset düyməsinə klik et

**Expected Result:**

Filterlər silinir

Bütün məhsullar göstərilir

**Actual Result:**

Filterlər sıfırlandı və bütün məhsullar göstərildi

**Status**:

Passed

**Test Case ID:** TC_045

**Test Case Title:** Uyğun məhsul olmayan filter seçimi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Çox dar filter seç

2.  Filtri tətbiq et

**Expected Result:**

"Məhsul tapılmadı" mesajı göstərilir

**Actual Result:**

Mesaj göstərildi

**Status:**

Passed

**Test Case ID:** TC_046

**Test Case Title:** Filter tətbiq olunmur

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Filter seç

2.  Apply düyməsinə klik et

**Expected Result:**

Filter tətbiq olunmalıdır

**Actual Result:**

Filter tətbiq olunmadı

**Status:**

Failed

**Test Case ID:** TC_047

**Test Case Title:** Filter nəticələrinin səhv göstərilməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Qiymət filteri seç

2.  Filtri tətbiq et

**Expected Result:**

Uyğun məhsullar göstərilməlidir

**Actual Result:**

Uyğunsuz məhsullar göstərildi

**Status:**

Failed

**Test Case ID:** TC_048

**Test Case Title:** Filter zamanı səhifənin donması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Filter seç

2.  Filtri tətbiq et

**Expected Result:**

Sistem stabil işləməlidir

**Actual Result:**

Səhifə dondu

**Status:**

Failed

**Test Case ID:** TC_049

**Test Case Title:** Filter dəyişdikdə nəticələrin yenilənməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Bir filter seç

2.  Sonra başqa filter seç

**Expected Result:**

Nəticələr yenilənir

**Actual Result:**

Nəticələr yeniləndi

**Status:**

Passed

**Test Case ID:** TC_050

**Test Case Title**: Filterdən sonra məhsula klik etmə

**Preconditions**:

İstifadəçi login olub

Filter tətbiq olunub

**Test Steps:**

1.  Filter tətbiq et

2.  Məhsula klik et

**Expected Result:**

Məhsul səhifəsi açılır

**Actual Result:**

Məhsul səhifəsi açıldı

**Status:**

Passed

**Test Case ID:** TC_051

**Test Case Title**: Filterdən sonra səhifəni yeniləmə

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Filter tətbiq et

2.  Səhifəni refresh et

**Expected Result:**

Filter ya qalır, ya sıfırlanır

**Actual Result:**

Filter sıfırlandı

**Status:**

Passed

**Test Case ID:** TC_052

**Test Case Title**: Filter seçilmədən tətbiq etmə

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1.  Heç bir filter seçmədən Apply et

**Expected Result:**

Heç bir dəyişiklik olmur

**Actual Result:**

Dəyişiklik olmadı

**Status:**

Passed

**Test Case ID:** TC_053

**Test Case Title**: Məhsul məlumatlarının yoxlanması

**Preconditions:**

İstifadəçi məhsul səhifəsinə daxil olub

**Test Steps:**

Məhsul adını, təsvirini, qiymətini yoxla

**Expected Result:**

Bütün məlumatlar düzgün və tam göstərilir

**Actual Result:**

Bütün məlumatlar düzgün və tam göstərilir

**Status:**

Passed

**Test Case ID:** TC_054

**Test Case Title**: Şəkillərin düzgün yüklənməsi

**Preconditions:**

İstifadəçi məhsul səhifəsinə daxil olub

**Test Steps:**

1 Şəkillərin yüklənməsini yoxla

2 Zoom funksiyasını test et

**Expected Result:**

Şəkillər keyfiyyətli və problemsiz açılır

**Actual Result:**

Şəkillər keyfiyyətli və problemsiz açılır

**Status:**

Passed

**Test Case ID:** TC_055

**Test Case Title**: Qiymət və discount yoxlanışı

**Preconditions:**

İstifadəçi məhsul səhifəsinə daxil olub

**Test Steps:**

1 Məhsul qiymətinə bax

2 Əgər endirim varsa, köhnə və yeni qiyməti müqayisə et

**Expected Result:**

Qiymət və endirim düzgün hesablanır

**Actual Result:**

Qiymət və endirim düzgün hesablanır

**Status:**

Passed

**Test Case ID:** TC_056

**Test Case Title**: Add to Cart funksiyası

**Preconditions:**

İstifadəçi məhsul səhifəsinə daxil olub

**Test Steps:**

"Səbətə əlavə et" düyməsinə klik et

**Expected Result:**

Məhsul səbətə əlavə olunur və bildiriş çıxır

**Actual Result:**

Məhsul səbətə əlavə olunur və bildiriş çıxır

**Status:**

Passed

**Test Case ID:** TC_057

**Test Case Title**: Stok statusunun yoxlanması

**Preconditions:**

İstifadəçi məhsul səhifəsinə daxil olub

**Test Steps:**

Stokda olan və olmayan məhsulları yoxla

**Expected Result:**

Stokda varsa sifariş mümkündür

Yoxdursa "Mövcud deyil" mesajı göstərilir

**Actual Result:**

Stokda varsa sifariş mümkündür,

Yoxdursa "Mövcud deyil" mesajı göstərilir

**Status:**

Passed

**Test Case ID:** TC_058

**Test Case Title**: Mobil və tablet uyğunluğu

**Preconditions:**

İstifadəçi sayta daxil olub

**Test Steps:**

1.  Fərqli cihazlarda səhifəni aç

2.  Saytın bütün bölmələrinə keçid et

**Expected Result:**

UI düzgün uyğunlaşır

**Actual Result:**

UI düzgün uyğunlaşır

**Status:**

Passed

**Test Case ID:** TC_059

**Test Case Title**: Məhsulun səbətə əlavə olunması

**Preconditions:**

İstifadəçi login olub

İstifadəçi məhsul səhifəsindədir

**Test Steps:**

1 "Səbətə əlavə et" düyməsinə klik et

2 Səbət səhifəsinə keç

**Expected Result:**

Məhsul səbətdə görünür

**Actual Result:**

Məhsul səbətdə görünür

**Status:**

Passed

**Test Case ID:** TC_060

**Test Case Title**: Məhsul sayının artırılması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Səbətə daxil ol

2 "+" düyməsinə klik et

**Expected Result:**

Məhsul sayı artır

Ümumi qiymət yenilənir

**Actual Result:**

Məhsul sayı artır

Ümumi qiymət yenilənir

**Status:**

Passed

**Test Case ID:** TC_061

**Test Case Title**: Məhsul sayının azaldılması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Səbətə daxil ol

2 "-" düyməsinə klik et

**Expected Result:**

Məhsul sayı azalır

Minimum limit (1) qorunur və ya məhsul silinir

**Actual Result:**

Məhsul sayı azalır

Minimum limit (1) qorunur və ya məhsul silinir

**Status:**

Passed

**Test Case ID:** TC_062

**Test Case Title**: Məhsulun silinməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Səbətə daxil ol

2 "Remove/Delete" düyməsinə klik et

**Expected Result:**

Məhsul səbətdən silinir

**Actual Result:**

Məhsul səbətdən silinir

**Status:**

Passed

**Test Case ID:** TC_063

**Test Case Title**: Maksimum stok limiti

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Səbətə daxil ol

2 Mövcud stokdan artıq say əlavə etməyə çalış

**Expected Result:**

Limit aşılmır

Xəbərdarlıq mesajı göstərilir

**Actual Result:**

1 Limit aşılmır

2 Xəbərdarlıq mesajı göstərilir

**Status:**

Passed

**Test Case ID:** TC_064

**Test Case Title**: Səbət məlumatlarının saxlanması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Məhsul əlavə et

2 Səhifəni refresh et və ya brauzeri bağla

3 Yenidən sayta daxil ol

4 Səbət bölməsinə keçid et

**Expected Result:**

Məhsullar səbətdə qalır

**Actual Result:**

Məhsullar səbətdə qalır

**Status:**

Passed

**Test Case ID:** TC_065

**Test Case Title**: İstifadəçi səbətdən checkout səhifəsinə keçə
bilirməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Məhsulu səbətə əlavə et

2 "Checkout" düyməsini kliklə

**Expected Result:**

Checkout səhifəsi düzgün açılır

**Actual Result:**

Checkout səhifəsi düzgün açılır

**Status:**

Passed

**Test Case ID:** TC_066

**Test Case Title**: Checkout səhifəsində məlumatların daxil edilməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsinə keç

2 Ad, soyad, telefon, ünvan daxil et

**Expected Result:**

Məlumatlar qəbul edilir və növbəti mərhələyə keçilir

**Actual Result:**

Məlumatlar qəbul edilir və növbəti mərhələyə keçilir

**Status:**

Passed

**Test Case ID:** TC_067

**Test Case Title**: Məcburi sahələr boş buraxıldıqda xəta mesajı

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsində sahələri boş saxla

2 "Continue" kliklə

**Expected Result:**

Müvafiq error mesajları göstərilir

**Actual Result:**

Müvafiq error mesajları göstərilir

**Status:**

Passed

**Test Case ID:** TC_068

**Test Case Title**: Yanlış formatda telefon daxil edilməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsinə keç

2 Telefon sahəsinə "abc123" daxil et

**Expected Result:**

"Yanlış format" xətası göstərilir

**Actual Result:**

"Yanlış format" xətası göstərilir

**Status:**

Passed

**Test Case ID:** TC_069

**Test Case Title**: Müxtəlif ödəniş üsulları (kart, nağd)

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsinə keç

2 Checkout səhifəsində sahələri doldur

3 "Continue" kliklə

4 Kart ilə ödəniş seç

**Expected Result:**

Kart məlumatları üçün forma açılır

**Actual Result:**

Kart məlumatları üçün forma açılır

**Status:**

Passed

**Test Case ID:** TC_070

**Test Case Title**: Invalid kart məlumatları daxil edilməsi

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsinə keç

2 Checkout səhifəsində sahələri doldur

3 "Continue" kliklə

4 Kart ilə ödəniş seç

5 Yanlış kart nömrəsi daxil et

**Expected Result:**

Ödəniş rədd edilir və mesaj göstərilir

**Actual Result:**

Ödəniş rədd edilir və mesaj göstərilir

**Status:**

Passed

**Test Case ID:** TC_071

**Test Case Title**: Uğurlu sifariş tamamlanması

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Checkout səhifəsinə keç

2 Checkout səhifəsində sahələri düzgün doldur

3 "Continue" kliklə

4 Kart ilə ödəniş seç

5 Kart məlumatlarını düzgün daxil et

6 Sifarişi tamamla ya kliklə

**Expected Result:**

Sifariş uğurla yaradılır və təsdiq mesajı göstərilir

**Actual Result:**

Sifariş uğurla yaradılır və təsdiq mesajı göstərilir

**Status:**

Passed

**Test Case ID:** TC_072

**Test Case Title**: Boş səbətlə checkout-a keçid

**Preconditions:**

İstifadəçi login olub

**Test Steps:**

1 Səbəti boş saxla

2 Checkout-a keç

**Expected Result:**

Xəbərdarlıq mesajı göstərilir

**Actual Result:**

Xəbərdarlıq mesajı göstərilir

**Status:**

Passed
