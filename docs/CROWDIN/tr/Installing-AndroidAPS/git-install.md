# Git yükleyin

## Windows

### 1. Git'i indir

- **You have to be online all of the time as Android Studio downloads several updates!**
- Herhangi bir git sürümü çalışması gerekir. For example [https://git-scm.com/download/win](https://git-scm.com/download/win).
- Make sure to note down the installation path. Bir sonraki adımda ihtiyacınız olacak.

```{image} ../images/Update_GitPath.png
:alt: Git kurulum yolu
```

### 2. Android Studio'da git yolunu ayarla

- Open File > Settings

  ```{image} ../images/Update_GitSettings1.png
  :alt: Android Studio - ayarları aç
  ```

- Click the small triangle next to Version Control (1.) to open the sub-menu.

- Click Git (2.).

- Make sure update method "Merge" (3.) is selected.

- Check if Android Studio can locate path to git.exe automatically by clicking the button "Test" (4.)

  ```{image} ../images/AndroidStudio361_09.png
  :alt: Android Studio ayarları
  ```

- If automatic setting is successful git version will be displayed.

- Click "OK" in the dialog box (1.) and "OK" in the settings window (2.).

  ```{image} ../images/AndroidStudio361_10.png
  :alt: Otomatik git kurulumu başarılı
  ```

- In case file git.exe cannot be found click "OK" in the dialog box (1.) and then the button with the three dots (2.).

- Use [search function](https://www.tenforums.com/tutorials/94452-search-file-explorer-windows-10-a.html) in windows explorer to find "git.exe" if you are unsure where it can be found. You are looking for git.exe located in binfolder.

- Select path to git.exe and make sure you selected the one in **\\bin\\** folder (3.) and click "OK" (4.).

- Close settings window by clicking "OK" button (5.).

  ```{image} ../images/AndroidStudio361_11.png
  :alt: Otomatik git kurulumu başarısız
  ```

### 3. Yeniden başlat

- Reboot your PC to update System Environment.

(check-git-settings-in-android-studio)=
### 4. Android Studio'da git ayarlarını kontrol edin

- Open Terminal window in Android Studio

- Enter `git --version` (without quotation marks and no spaces between the two - \[minus sign\]!) and press Return

  ```{image} ../images/AndroidStudio_gitversion1.png
  :alt: git - -version
  ```

- If git is installed and connected properly you will receive an information about the installed version that looks as follows:

  ```{image} ../images/AndroidStudio_gitversion2.png
  :alt: git-version durumu
  ```

## Mac

- Herhangi bir git sürümü çalışması gerekir. For example [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
- Use homebrew to install git: `` `$ brew install git` ``.
- Git'i yüklemeyle ilgili ayrıntılar için [resmi git belgelerine](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) bakın.
- Git'i homebrew aracılığıyla kurarsanız, herhangi bir tercihi değiştirmenize gerek yoktur. Her ihtimale karşı: Android Studio - Tercihler altında bulabilirsiniz.
