# M1_cocoapod

m1 실리콘에서 pod 설치하는 방법

1.arm64로 지정하여 ffi설치

sudo arch -x86_64 gem install ffi
sudo gem install cocoapods

2.레파지토리 지정 후 arm64로 지정하여 pod install

arch -x86_64 pod install
