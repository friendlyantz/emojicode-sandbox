# emojicode-sandbox  
                     
## 1. install emoji-code:

https://www.emojicode.org/docs/guides/install.html

Linux(wget):
```sh
wget https://github.com/emojicode/emojicode/releases/download/v1.0-beta.2/Emojicode-1.0-beta.2-Linux-x86_64.tar.gz -O emojicode.tar.gz \
&& tar -xzf emojicode.tar.gz && rm emojicode.tar.gz \
&& cd Emojicode-1.0-beta.2-Linux-x86_64 && ./install.sh \
&& cd .. && rm -r Emojicode-1.0-beta.2-Linux-x86_64
```
> note: if you encounter error when compiling on Linux:
```sh
sudo apt install libncurses5
```

## 2. write code:

- file ext can be .🍇 or .emojic
- start with: 🏁🍇
- end with: 🍉

## 3. compile:

```sh
emojicodec filename.🍇 # OR filename.emojic
```
## 4. run:
```sh
./filename
```
