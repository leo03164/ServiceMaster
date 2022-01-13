<template>
  <div class="outBox">
        <div class="title">
            <h2>Hi Master! 你可以先看看... </h2>
        </div>
       <div class="outBox__smallBox">
            <div class="jobBox">
                <img class="jobBox__img" src="@\assets\icon\TwoChatMan.png" style="padding-top:30px" />
                <h2 class="desription">學科/家教</h2>  
            </div>
            <div class="jobBox">
                <img class="jobBox__img" src="@/assets\icon\Group 31.png" style="padding-top:30px" />
                <h2 class="desription">日常翻譯</h2>           
            </div>
            <div class="jobBox">
                <img class="jobBox__img" src="@/assets\icon\TossAcrobatics.png" style="padding-top:30px" />
                <h2 class="desription">活動表演</h2>
            </div>
        </div>
        <div class="buttonBox">
            <div class="jobBox">
                <img class="jobBox__img" src="@/assets\icon\RainbowRingWomen.png" style="padding-top:30px" />
                <h2 class="desription">技能導師</h2>
            </div>
            <div class="jobBox">
                <img class="jobBox__img" src="@/assets\icon\WatercolorPalette.png" style="padding-top:30px" />
                <h2 class="desription">平面設計</h2> 
            </div>
            <div class="jobBox">
                <img class="jobBox__img" src="@/assets\icon\UIDesign.png" style="padding-top:30px" />
                <h2 class="desription">程式設計</h2>
            </div>
        </div>        
    </div>
</template>

<script>
export default {
  name: "JobBox",
};
</script>

<style type="text/css">
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&display=swap');
    *{
        margin: 0;
        padding: 0;
        list-style: none;
        font-family: 'Noto Sans TC', sans-serif;
    }

    .outBox{ 
        width:100%;
        height: 500px;
        /* 外框 */
    }

    .title{
        padding: 10px 20px;
        /* 大標題 */
    }
    
    .buttonBox{
        width:100%;
        display: flex;
        /* 包住所有職業類型 */
    }

    .jobBox{
        width: 200px;
        padding: 5px;
        margin: 5px;
        display: block;
        background-color:rgb(241, 233, 233);
        text-align: center;
        flex-direction: row;
        box-shadow: 1px 1px #888888;
        border-radius: 10px;
        /* 各項職業類型 */
    }

    .jobBox img{
        padding-top: 3px;
        /* 職業圖示 */
    }

    .jobBox h2{
        font-size: 14px;
        /* 職業文字 */
    }
</style>
