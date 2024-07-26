<script setup lang="ts">
</script>


<template>
    <div class="about">
        <h1>This is a Crew page</h1>
        <div>
            <h2 class="team">Team</h2>
            <img src="https://img.recraft.ai/U-MQXvcHR_UBgeqWRItt9C2RtMutop0xK2vZPi-tm9s/rs:fit:1024:1024:0/q:80/g:no/plain/abs://prod/images/f99a816c-c059-48ff-96c8-8c4ad1a1e088@avif"
                alt="photo" width="200px" height="200px">
            <a href="https://github.com/OUSee" class="tag">HACKERMAN</a>
        </div>
    </div>
</template>

<style scoped>
@media (min-width: 1024px) {
    .about {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        padding-top: 0;
        margin: 0;  
    }
    .team{
        text-align: center;
        margin-bottom: 20px;
    }
    .tag{
        display: block;
        text-align: center;
        margin-top: 20px;
    }
    img{
        border-radius: 50%;
        padding: 3px;
        outline: 1px solid #00bd7e;
    }
}
</style>