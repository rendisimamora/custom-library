<template>
  <div class="wrapper">
    <div class="editor-card d-flex">
      <img
        class="editor-card-avatar"
        src="https://static.femaledaily.com/dyn/70/images/user-pics/8cfa98979828b03949df998669bcca01.jpg"
        alt="Rendi Simamora"
      />

      <div class="ml-2">
        <p class="font-weight-bold mb-0">annedean</p>
        <p class="caption grey--text lighten-5">Associate Editor</p>
      </div>
    </div>
    <div class="product-card pa-2">
      <div class="product-card-editor d-flex flex-column">
        <img
          class="product-card-image"
          src="https://static.femaledaily.com/dyn/150/images/prod-pics/bd497870029ece8f83e861065f10dc56.jpg"
          alt="Image"
        />
        <p class="font-weight-bold my-2">4.6 (9)</p>
        <p class="product-card-label mb-1 subheading font-weight-bold">
          NYX
        </p>
        <p class="product-card-title mb-1 subtitle-1">
          Bare With Me Tinted Skin Veil Bare With Me Tinted Skin Veil Bare With
          Me Tinted Skin Veil
        </p>
        <p class="grey--text lighten-5">Beige Caramel</p>
      </div>
    </div>
  </div>
</template>

<script>
require('../assets/css/style.css')
export default {
  name: 'CardProducts'
}
</script>

<style lang="scss">
$color-primary: #db284e;

.wrapper {
  max-width: 200px;
}

.editor {
  &-card {
    margin: 0 0 -10px 16px;
    &-avatar {
      width: 50px;
      height: 50px;
      border-radius: 100%;
      border: 0.5px solid #e0e0e0;
      object-fit: cover;
      margin-top: 10px;
    }
  }
}

.product {
  &-card {
    min-height: 351px;
    border: 1px solid #e0e0e0;
    overflow-wrap: break-word;
    border-radius: 10px;
    &-image {
      max-width: 100%;
      max-height: 100%;
    }
    &-label {
      &:hover {
        cursor: pointer;
        color: $color-primary;
      }
    }
    &-title {
      cursor: pointer;
      display: -webkit-box;
      white-space: normal;
      -webkit-line-clamp: 2;
      -webkit-box-orient: vertical;
      overflow: hidden;
    }
  }
}
</style>
