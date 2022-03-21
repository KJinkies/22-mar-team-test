<template>

    <div class="body_kj" >

        <h1 style="text-align:center" >KJs Div</h1>

        <div class="img_cont_kj" >
            <div class="img_kj img_kj_1 " ></div>
            <div class="img_kj img_kj_2"></div>
            <div class="img_kj img_kj_3"> </div>
        </div>

    </div>

</template>

<style scoped>

.img_cont_kj{
    display: flex;
    justify-content: center;
}

.img_kj{
    height: 300px;
    width: 250px;
    margin: 0px 5px 20px 0px;

}

.body_kj{
    background-color: pink;
}

.img_kj_1{
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxPO4zW3Sb_9urQO957aZoE9UdK3KSadqxpFNX7u3gaVelVPgQeDwXxDcjUAIgDI1GX98&usqp=CAU');
    background-size:     cover;                     
    background-repeat:   no-repeat;
    background-position: center center; 
}

.img_kj_2{
    background-image: url('https://www.aspca.org/sites/default/files/dog-care_dog-bite-prevention_main-image.jpg');
    background-size:     cover;                     
    background-repeat:   no-repeat;
    background-position: center center; 
}


.img_kj_3{
    background-image: url('https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/smartest-dog-breeds-lead-1587757081.jpg?crop=1.00xw:1.00xh;0,0&resize=640:*');
    background-size:     cover;                     
    background-repeat:   no-repeat;
    background-position: center center; 
}




</style>