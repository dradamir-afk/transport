<template>
    <div class="container">
        <h1 class="welcome">
        Welcome to your <br/> Logistic Capasity Optimization Tool
        </h1>
        <form>
            <div class="area">
                <div class="autho">
                    <input type="text" class="username" placeholder="Your ABI Username">
                    <input type="text" class="password" placeholder="Your ABI Password">
                </div>
                    <div class="submitcont">
                    <input type="submit" class="submit" value="Login">
                </div>
            </div>
        </form>
        <button class="support">Support</button>
        <div class="logo">
                <img src="https://img.icons8.com/ios/50/000000/cute-termite.png"/>
        </div>
        <div class="poweredby">
            <img src="https://img.icons8.com/ios/50/000000/ant.png"/>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@100&display=swap');
.container{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
}

.welcome {
    font-family: 'Raleway', sans-serif;
    font-size: 44px;
    text-align: center;
    margin-top: 200px;
}
.area{
    display: flex;
    flex-direction: column;
    width: 580px;
    height: 150px;
    margin-top: 50px;
}
.autho{
    
    display: flex;
    justify-content: center;
    align-items: center;
    
}
.username{
    font-size: 15px;
    height: 60px;
    width: 345px;
    margin-right: 10px;
    border: none;
}
.password{
    font-size: 15px;
    height: 60px;
    width: 345px;
    border: none;
}
.submitcont{
    height: 60px;
    width: 580px;
    margin-top: 20px;
    display: flex;
    justify-content: center;
}
.submit{
    font-size: 15px;
    width: 100%;
    height: 100%;
    border: none;
    background-color: #5198fc;
    border-radius: 15px;
    color: white;
}

.support{
    width: 150px;
    height: 35px;
    margin-top: 30px;
    background-color: #5a81fb;
    border: none;
    border-radius: 15px;
    color:white;
    font-size: 15px;
}

.logo{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
}

.poweredby{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 150px;
}
</style>