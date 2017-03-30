Para gerar release:

-> cordova build --release android

Para assinar usando a chave:

-> jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore my-release-key.keystore familias.apk alias_name

senha: celkandroid
