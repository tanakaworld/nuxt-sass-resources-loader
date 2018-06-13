<template>
  <div>
    <nuxt/>
  </div>
</template>

<style lang="sass">
  html
    font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif
    font-size: 16px
    word-spacing: 1px
    -ms-text-size-adjust: 100%
    -webkit-text-size-adjust: 100%
    -moz-osx-font-smoothing: grayscale
    -webkit-font-smoothing: antialiased
    box-sizing: border-box

    *
      box-sizing: border-box
      margin: 0
      &:before, &:after
        box-sizing: border-box
        margin: 0

    .button--green
      display: inline-block
      border-radius: 4px
      border: 1px solid $color-green
      color: $color-green
      text-decoration: none
      padding: 10px 30px
      &:hover
        color: #fff
        background-color: $color-green

    .button--grey
      display: inline-block
      border-radius: 4px
      border: 1px solid $color-dark-gray
      color: $color-dark-gray
      text-decoration: none
      padding: 10px 30px
      margin-left: 15px
      &:hover
        color: #fff
        background-color: $color-dark-gray

    .container
      min-height: 100vh
      display: flex
      justify-content: center
      align-items: center
      text-align: center

      .title
        font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif
        display: block
        font-weight: 300
        font-size: 100px
        color: $color-dark-gray
        letter-spacing: 1px

      .subtitle
        font-weight: 300
        font-size: 42px
        color: $color-blue
        word-spacing: 5px
        padding-bottom: 15px

      .links
        padding-top: 15px
</style>
