<template>
    <header class="header">
        <nav class="nav">
            <span class="title"><a href="#">devChallenges.io</a> </span>
            <ul class="order_list">
                <li class="list"><a href="#">colors</a></li>
                <li class="list"> <a href="#">typhografy</a> </li>
                <li class="list"> <a href="#">spaces</a> </li>
                <li class="list"> <a href="#">buttons</a></li>
                <li class="list"> <a href="#">imputs</a></li>
                <li class="list"> <a href="#">grind</a></li>

            </ul>
        </nav>
    </header>
</template>
<style>

.order_list{
    display: flex;
    flex-direction: column;
    list-style: none;
    margin-left: 20px;
    width: 100px;
    margin-right: 0px;
    
    

}

.list a{
    text-decoration: none;
}
.list a:hover{
    color: burlywood;
}

.list{
    margin-top: 20px;
    width: 150px;
}

.title a{
    text-decoration: none;
}

.title{
    margin-top: 60px;
    margin-left: 20px;
    font-weight: bold;
}
</style>