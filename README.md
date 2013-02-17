
# VIM-THAI-KEYS

เคยมีปัญหานี้ไม่ครับ พิมพ์ๆ ภาษาไทยใน VIM อยู่ดีๆ แล้วกด ESC ออกมา command mode
แล้วใช้คำสั่งอะไรไม่ได้เลยเพราะว่าคีย์บอร์ดมันเป็นภาษาไทยอยู่ ต้องเปลี่ยนกลับเป็นภาษาอังกฤษก่อนถึงจะทำงานต่อได้?

Ever got frustrated when you have to type in Thai while in VIM and found that all the
command keys no longer work because your keyboard is in the Thai language?

Plugin ตัวนี้ทำมาเพื่อการนี้โดยเฉพาะเลยครับ ซึ่งจริงๆ แล้วมันก็เป็นแค่ไฟล์ mapping ยาวๆ ไฟล์นึง ที่ map
คีย์ภาษาไทยทั้งหมดให้เป็นคำสั่งที่ตรงกันถ้ากดปุ่มเป็นภาษาอังกฤษ ตัวอย่างเช่น ฟ ห ก ด ก็ map เป็น a s d และ f
ตามลำดับ ถ้าลงไว้แล้วไม่ต้องเปลี่ยนภาษาเลยครับ

This plugin is a very simple set of bindings for Thai characters to normal vim commands
that is on the same key, for example ฟ ห ก and ด is mapped to `a` `s` `d` and `f`
respectively so you do not have to switch language when you're back in command mode
anymore!

ถ้ามีเหตุให้ต้องพิมพ์ภาษาไทยใน VIM แนะนำให้ลองเอาไปใช้ดูครับ ถ้าใช้
[Vundle](https://github.com/gmarik/vundle) ก็เพิ่มบรรทัดนี้เข้าไปใน `.vimrc` ได้เลยครับ

If you have need to type Thai in VIM, this plugin might prove useful to you. If you are
using Vundle, just add this line to your `.vimrc`:

```vim
Bundle 'chakrit/vim-thai-keys'
```

จากนั้นก็พิมพ์ `:BundleInstall` ใน VIM อีกทีแค่นี้ก็เรียบร้อยแล้วครับ

And then do `:BundleInstall` and you're good to go : - )

# SUPPORT / CONTRIBUTE

ถ้ามีปัญหาหรือข้อสงสัยก็เขียนมาเป็น [GitHub
Issue](https://github.com/chakrit/vim-thai-keys/issues/new) ได้เลยครับ หรือว่าทักมาทาง Twitter
[@chakrit](https://twitter.com/chakrit) ก็ได้ครับ

Just open a new [GitHub Issue](https://github.com/chakrit/vim-thai-keys/issues/new) or just
ping me on Twitter [@chakrit](https://twitter.com/chakrit).

หรือว่าถ้าอยากแก้ให้เลยแล้วส่งมาเป็น Pull Requests ก็ยินดีนะครับ : - )

Pull requests welcome of course!

