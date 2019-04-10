<template>
</template>

<script>
export default {
}
</script>

<style lang="sass?indentedSyntax=true">
.contant
  position: relative
  left: 13%
  display: flex
  font-family: SegoeUI
  justify-content: space-between
  max-width: 1055px
@media screen and (max-width: 1280px)
  .contant
    left: 10%
    max-width: 946px
.bottomBar
  display: flex
  flex-direction: column
  max-width: 196px
.bottomBar h4
  color: white
  font-size: 14px
  font-weight: 600
  margin-bottom: 3%
.bottomBar a
  font-size: 11px
  line-height: 1.94
  color: #c5c5c5
.bottomBar:nth-child(3) a
  padding:
    top: 13px
.bottomBar p
  font-size: 11px
  color: #c5c5c5
  line-height: 1.94
.bottomBar img
  position: relative
  top: 10px
  left: 0px
  padding:
    top: 7%
    bottom: 7%
.bottomBar .main
  display: flex
  max-width: 53px
.uni
  margin-top: 0%
  max-width: 27px
.items
  display: flex
  flex-direction: row
  justify-content: space-between
  max-width: 110px
.connect
  margin:
      top: 9%
      bottom: 9%
  max-width: 17px
  max-height: 17px
.logo
  margin-top: 0%
  max-width: 41px
</style>
