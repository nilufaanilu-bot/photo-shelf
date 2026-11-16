# Photo Shelf APK (GitHub diye build)

Ei folder-er shob file GitHub-e upload korle GitHub nijei APK banie dibe. Tomar computer-e kichu install korte hobe na.

## Step by step

1. https://github.com e login koro (account na thakle free account banao).
2. Upore + chepe **New repository**. Nam dao `photo-shelf`. Public rakho (Public hole build free). **Create repository** chap.
3. Repository-te **uploading an existing file** link-e chap (ba Add file > Upload files).
4. Ei folder-er shob file select kore upload koro, **sudhu `build-apk.yml` ar `README.md` badhe**. Folder banate hobe na, file gulo ja ache tai-i upload hobe (nam-e `__` thakle thik ache, GitHub nijei folder banie nibe). Tarpor **Commit changes** chap.
5. Ekhon **Add file > Create new file** chap. Nam-er ghore ei line tuku lekho (slash lekhar sathe sathe folder hoye jabe):
   `.github/workflows/build-apk.yml`
6. `build-apk.yml` file-er lekha shob copy kore ei ghore paste koro, tarpor **Commit changes** chap.
7. Upore **Actions** tab-e jao. "Build APK" cholche. 3-6 minute lagbe. Shobuj tick hole shesh.
8. Repository-r ekdom main page-e dan dike **Releases** > **Photo Shelf APK** > `PhotoShelf.apk` chap. Phone-e download hobe.
9. Download howa file chap. Phone "Install unknown apps" allow korte bolle allow koro, tarpor Install.

## Jodi build fail kore
Actions tab-e lal cross-wala run-e chap, nicher error-er lekha copy kore Claude-ke pathao.

## Notes
- Photo gulo app-er vitore, phone-e save hoy. Kothao upload hoy na, app-er internet permission-o nei.
- App uninstall korle ba Settings theke app-er data clear korle photo muche jabe.
- Notun version banate chaile file bodlie abar commit koro, APK nijei notun hoye Releases-e update hobe.
