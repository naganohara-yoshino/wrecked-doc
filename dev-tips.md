# 一些开发提示


## `chat_screen`用法

```
label example:

    image fr = Frame("images/OTHER/background.png")

    scene fr

    show fr at blur_background

    window hide

    python: 
        untitled = "images/OTHER/Untitled.png"
        meme0 = "images/OTHER/meme.jpg"
        meme1 = "images/OTHER/meme1.png"
        meme2 = "images/OTHER/meme2.jpg"

        dialog = [
            {"name": "FakeSeek", "content": "我不敢苟同他的观点，我个人认为这个意大利面就应该拌42号混凝土，因为这个螺丝钉的长度，它很容易会直接影响到挖掘机的扭矩，你知道吧😆", "avatar": untitled, "from_myself" : True},
            {"name": "DeepGPT", "content": "典型的碳基生物思维😤😤😤", "avatar": untitled},
            {"name": "DeepGPT", "image": meme0, "avatar": untitled},
            {"name": "A", "content": "111", "avatar": untitled, "extra_display": "25:61"},
            {"name": "DeepGPT", "image": "images/OTHER/meme1.png", "avatar": untitled},
            {"name": "B", "content": "222", "avatar": untitled},
            {"name": "C", "content": "333", "avatar": untitled},
        ]


    show screen chat_screen("测试(1000)", dialog)
    
    pause

    scene fr at blur_background_recover

    pause 0.8
    
    window show
    window hide

    show screen chat_screen("测试笑谈(1000)", dialog)
    

    pause

    scene fr at blur_background_recover

    pause 0.8
    
    window show

```