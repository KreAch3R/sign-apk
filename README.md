# Sign-apk

A wrapper of [patrickfav's uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) that can re-sign any apk you throw at it, with the keystore and key of your choice.

## Prerequisites
 * an APK file (it doesn't matter if it's signed or not)
 * a Keystore file with a Key (and their passwords)

## What it's for

Use it to sign any apk with whatever you want, with the speed and ease of your terminal!

## How it works

It is an wrapper/script for patrickfav's uber-apk-signer. The jar itself provides a lot more options, but there is no way to remember all the arguments every time you want to sign an apk. This wrapper provides all the necessary arguments to resign any apk by default, and only leaves the apk file and the keystore file to the user.