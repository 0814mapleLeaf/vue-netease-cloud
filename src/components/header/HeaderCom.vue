<template>
    <nav>
        <router-link to="/login">
            <svg t="1650612890748" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"
                 p-id="2030" width="20" height="20">
                <path d="M849.1 128 174.9 128c-25.9 0-46.9 21-46.9 46.9l0 34.2c0 25.9 21 46.9 46.9 46.9l674.2 0c25.9 0 46.9-21 46.9-46.9l0-34.2C896 149 875 128 849.1 128z"
                      p-id="2031"></path>
                <path d="M849.1 768 174.9 768c-25.9 0-46.9 21-46.9 46.9l0 34.2c0 25.9 21 46.9 46.9 46.9l674.2 0c25.9 0 46.9-21 46.9-46.9l0-34.2C896 789 875 768 849.1 768z"
                      p-id="2032"></path>
                <path d="M849.1 448 174.9 448c-25.9 0-46.9 21-46.9 46.9l0 34.2c0 25.9 21 46.9 46.9 46.9l674.2 0c25.9 0 46.9-21 46.9-46.9l0-34.2C896 469 875 448 849.1 448z"
                      p-id="2033"></path>
            </svg>
        </router-link>
        <div>
            <router-link to="/profile">我的</router-link>
            <router-link to="/">发现</router-link>
            <router-link to="/yun-cun">云村</router-link>
            <router-link to="/video">视频</router-link>
        </div>
        <router-link to="/search">
            <svg t="1650613099629" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"
                 p-id="2876" width="20" height="20">
                <path d="M938.88694045 899.74010311l-272.16372623-272.16372622c49.71026963-58.40956682 79.53643141-133.59634963 79.53643141-216.23967289 0-184.549376-149.75218725-334.30156325-334.30156326-334.30156325S77.03514075 226.787328 77.03514075 411.336704s149.75218725 334.30156325 334.30156325 334.30156325c82.02194489 0 157.2087277-29.82616178 215.61829452-78.91505303l272.16372623 272.16372623c5.59240533 5.59240533 12.42756741 8.07791882 19.88410784 8.0779188 6.83516208 0 14.29170252-2.48551348 19.88410786-8.0779188 10.5634323-11.18481067 10.5634323-28.58340503 0-39.14683734zM126.74541037 411.336704C126.74541037 254.1279763 254.1279763 126.74541037 411.336704 126.74541037s284.59129363 128.0039443 284.59129363 284.59129363-128.0039443 284.59129363-284.59129363 284.59129363S126.74541037 567.92405333 126.74541037 411.336704z"
                      p-id="2877"></path>
            </svg>
        </router-link>
    </nav>
</template>

<script>
    export default {
        name: "HeaderCom",
        data() {
            return {}
        },
        setup(){

        },
    }
</script>

<style scoped lang="less">
    nav {
        display: flex;
        justify-content: space-between;
        margin-bottom: 10px;

        div {
            width: 200px;
            display: flex;
            justify-content: space-between;

            a {
                color: #000;
                text-decoration: none;
            }
        }
    }

    .router-link-active {
        font-weight: bold;
    }
</style>