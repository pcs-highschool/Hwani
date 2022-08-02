<template>
    <div>
        <h2 v-if="menuTitle">
            {{menuTitle}}
        </h2>
        <p v-else>
            실패
        </p>
        <ul>
            <li>메뉴1</li>
            <li>메뉴2</li>
            <li>메뉴3</li>
            <li>메뉴4</li>
            <li>메뉴5</li>
            <li>메뉴6</li>
            <li>메뉴7</li>
            <li>메뉴8</li>
        </ul>
    </div>
</template>

<script>
export default {
    props : {
        menuTitle : String,
    }
}
</script>

<style>

</style>