<template>
  <svg
    width="24"
    height="24"
    viewBox="0 0 80 80"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M12 22V58C12 61.3137 14.6863 64 18 64H62C65.3137 64 68 61.3137 68 58V30C68 26.6863 65.3137 24 62 24H22.5C21.3954 24 20.5 23.1046 20.5 22C20.5 20.8954 21.3954 20 22.5 20H59.6586C58.8349 17.6696 56.6124 16 54 16H18C14.6863 16 12 18.6863 12 22ZM52 43C52 40.7909 53.7909 39 56 39C58.2091 39 60 40.7909 60 43C60 45.2091 58.2091 47 56 47C53.7909 47 52 45.2091 52 43Z"
      :fill="color"
    />
  </svg>
</template>

<script>
export default {
  name: 'WalletIcon',
  props: {
    color: String,
    default: () => '#000'
  }
}
</script>
