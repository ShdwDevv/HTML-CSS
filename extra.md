```html
<style>
    .outer-veri{
        margin-bottom: 10px;
    }
    p{
        font-family: Arial;
        margin-top: 0px;
        margin-bottom: 0px;
    }
    .hori{
        display: inline-block;
        vertical-align: middle;
    }
    .hori-1{
        width: 100px;
    }
    .hori-2{
        width: 150px;
    }
    .hori-3{
        width: 60px;
    }
    img{
        width: 80px;
        height: 80px;
        object-fit: cover;
        border-radius: 50px;
    }
    .topic{
        font-weight: bold;
    }
    .veri-1,.veri-2{
        margin-bottom: 5px;
    }
    button{
        background-color: rgb(10, 111, 213);
        color: #fff;
        padding:8px 18px;
        border-radius: 3px;
        border:none;
        font-weight: bold;
    }
    
</style>
<div class="outer-veri">
    <div class="hori hori-1">
        <img src="./cat.jpg" alt="cat">
    </div>
    <div class="hori hori-2">
        <div class="veri veri-1">
            <p class="topic">oliver</p>
        </div>
        <div class="veri veri-2">
            <p class="sub">the cat</p>
        </div>
        <div class="veri veri-3">
            <p class="category">Popular</p>
        </div>
    </div>
    <div class="hori hori-3">
        <button>Follow</button>
    </div>
</div>
<div class="outer-veri">
    <div class="hori hori-1">
        <img src="./cat2.jpg" alt="cat">
    </div>
    <div class="hori hori-2">
        <div class="veri veri-1">
            <p class="topic">Mimi</p>
        </div>
        <div class="veri veri-2">
            <p class="sub">Sleepy cat</p>
        </div>
        <div class="veri veri-3">
            <p class="category">Popular</p>
        </div>
    </div>
    <div class="hori hori-3">
        <button>Follow</button>
    </div>
</div>
<div class="outer-veri">
    <div class="hori hori-1">
        <img src="./dog.jpg" alt="cat">
    </div>
    <div class="hori hori-2">
        <div class="veri veri-1">
            <p class="topic">Rex</p>
        </div>
        <div class="veri veri-2">
            <p class="sub">Happy Buildog</p>
        </div>
        <div class="veri veri-3">
            <p class="category">Popular</p>
        </div>
    </div>
    <div class="hori hori-3">
        <button>Follow</button>
    </div>
</div>
```