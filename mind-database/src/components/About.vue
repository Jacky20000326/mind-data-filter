<template>
    <img src="../assets/content1.png" alt="">
    <div class="about">
        <div class="txt">
            <h3>關於我們</h3>
            <div class="txt">
                <p>Bô Iàu-kín是台語「沒關係」的拼音，</p> 
                <p>希望大家在遇到生命中的各種難題時， </p>   
                <p>能夠跟自己說一聲「沒關係」的話就好了。</p>
                <hr color="845A3E">
                <p>我們是一群來自台灣各地的大學生，</p>
                <p>致力於推廣校園心理健康。</p>
                <p> 透過校園心理資料庫、心理地圖的建置，</p>
                <p>以及製作適合學生及青少年吸收的心理相關內容，</p>
                <p> 希望能降低學生在尋求心理協助及相關資源的時間</p>
                <p> 與心力成本，也希望能喚起大眾對此議題的重視。</p>
                <hr color="845A3E">
            </div>
            
        </div>   
    </div>
        
</template>

<script>
export default {

}
</script>

<style scoped>

.about{
    width: 100%;
    height: 689px;

}

img{
    width: 100%;
    height: 100%;
    position: absolute;
    z-index: -1;

}
h3{
    font-size: 48px;
    margin-top: 100px;
    margin-left: 50px;
    color: #845A3E;
}
.txt{
    margin-left: 50px;
    margin-top: 90px;
}

p{
    font-size: 24px;
    color: #845A3E;
}
hr{
    width: 62px;
    margin: 40px 0px 40px 0px;
    
}
</style>