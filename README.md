# M1_cocoapod

m1 실리콘에서 pod 설치하는 방법

## 1. arm64로 지정하여 ffi설치

sudo arch -x86_64 gem install ffi
sudo gem install cocoapods

## 2. 레파지토리 지정 후 arm64로 지정하여 pod install

arch -x86_64 pod install

# 깃 이메일 설정

## 1. 이메일 확인

git config user.email

## 2. 이메일 변경

git config --global user.email 바꿀@이메일주소.com
