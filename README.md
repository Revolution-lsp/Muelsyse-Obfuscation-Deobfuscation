# Muelsyse-Obfuscation-Deobfuscation
An Android app used for image obfuscation and deobfuscation

Supported environment scope:\
minSdk = 24&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Android 7.0\
targetSdk = 34&nbsp;&nbsp;Android 17

This app was created to free image processing from the computer and to process and save images with minimal loss.\
As a result, the app was designed without any limit to scale images down below 8 megapixels. That said, very large images may exceed Android’s per-app memory limit and cause a crash. This will be addressed in a later version. If your image is really large and you want to restore it without lowering the resolution, please use my other open-source program:
https://github.com/Revolution-lsp/Gilbert-Curve-Scramble

Also, since existing Gilbert-curve obfuscation/deobfuscation websites all impose an 8-megapixel scaling limit, obfuscated images produced by my program that exceed 8 megapixels will suffer image distortion if they are scaled down by those websites and then deobfuscated there. This compatibility issue is unavoidable. That said, images obfuscated by those websites can be deobfuscated with this program without the above problem.
