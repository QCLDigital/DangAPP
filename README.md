# DangAPP
---git---
echo "# DangAPP" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/QCLDigital/DangAPP.git
git push -u origin main
---cocoapods---
cd ~/.cocoapods/repos
rm -rf *
---React Native INIT--
cp -r DangAPP/.git /Users/Admin/Documents/1
cp -r DangAPP/README.md /Users/Admin/Documents/1
npx react-native init DangAPP
cp -r 1/README.md /Users/Admin/Documents/DangAPP
cp -r 1/.git /Users/Admin/Documents/DangAPP
---Start APP--
npx react-native start
npx react-native run-android
npx react-native run-ios
