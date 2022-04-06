<template>
  <div class="page">
      <!-- 동적라우터를 이용하여 $route의 값을 저장하고 가져올수있음 -->
    <h3>{{$route.params.page}} 페이지 입니다</h3>
  </div>
</template>

<script>

export default {
  name: 'PageComponent',
  
}
</script>
