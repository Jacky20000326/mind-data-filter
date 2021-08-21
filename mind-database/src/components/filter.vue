<template>
    <img src="../assets/content2.png" alt="">
    <div class="filter">
        <h3>查查附近的校園心輔資源吧！</h3>
        <div class="filter-section">
            <div class="region-filter">
                
                <select name="cars" id="cars">
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="mercedes">Mercedes</option>
                    <option value="audi">Audi</option>
                    
                </select>
                <i class="fas fa-caret-up"></i>
            </div>
            <div class="school-filter">
                <select name="cars" id="cars">
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="mercedes">Mercedes</option>
                    <option value="audi">Audi</option>
                </select>
                <i class="fas fa-caret-up school"></i>
            </div>
            
        </div>
        <p>或者...</p>
        <div class="inpur-filter">
            <input type="text">
        </div>
        <button>開始收尋</button>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img{
    width: 100%;
    height: 100%;
    position: absolute;
    z-index: -1;

}
.filter{
    width: 100%;
    height: 789px;
    display: flex;
    align-items: center;
    flex-direction: column;
   
    
}

h3{
    font-size: 48px;
    margin-top: 85px;
    color: #845A3E;
}
p{
    font-size: 30px;
    margin: 20px 0px 20px 0px;
    color: #8C705D;
}
.filter-section{
    display: flex;
    margin-top: 42px;
    position: relative;
}

select{
    width: 320px;
    height: 64px;
    margin: 56px;
    font-size: 30px;
    padding-left: 40px;
    appearance: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    
    

}
.fas.fa-caret-up{
    position: absolute;
    font-size: 40px;
    top: 40%;
    left: 38%;
}
.fas.fa-caret-up.school{
    position: absolute;
    font-size: 40px;
    top: 40%;
    left: 88%;
}
option{
    margin-left: 50px;
}
</style>