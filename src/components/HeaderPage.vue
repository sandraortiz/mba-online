<template>
  <!-- <div>
    <div class="footer">
      <b-container class="bv-footer-row">
        <b-row>
          <b-navbar type="dark" variant="dark">
            <b-navbar-nav class="items">
              <b-nav-item class="item" href="#solicita_info">Logo</b-nav-item>
              <b-nav-item class="item" href="#mba_online"
                >MBA Online</b-nav-item
              >
              <b-nav-item class="item" href="#ranking">Ranking</b-nav-item>
              <b-nav-item class="item" href="#director_pala"
                >Palabras <br />
                del Director</b-nav-item
              >
              <b-nav-item class="item" href="#porque_esan"
                >¿Por qué el MBA <br />
                Semipresencial <br />
                De ESAN?</b-nav-item
              >
              <b-nav-item class="item" href="#se_parte"
                >Sé parte del <br />
                MBA <br />
                Semipresencial</b-nav-item
              >
              <b-nav-item class="item" href="#beneficios"
                >Beneficios</b-nav-item
              >
              <b-nav-item class="item" href="#porque_mba_esan"
                >¿Por qué un <br />
                MBA en ESAN?</b-nav-item
              >
            </b-navbar-nav>
          </b-navbar>
          <b-navbar toggleable="lg" type="dark" variant="info">
            <b-navbar-brand href="#">NavBar</b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
              <b-navbar-nav>
                <b-nav-item href="#">Link</b-nav-item>
                <b-nav-item href="#" disabled>Disabled</b-nav-item>
              </b-navbar-nav>

              <b-navbar-nav class="ml-auto">
                <b-nav-form>
                  <b-form-input
                    size="sm"
                    class="mr-sm-2"
                    placeholder="Search"
                  ></b-form-input>
                  <b-button size="sm" class="my-2 my-sm-0" type="submit"
                    >Search</b-button
                  >
                </b-nav-form>

                <b-nav-item-dropdown text="Lang" right>
                  <b-dropdown-item href="#">EN</b-dropdown-item>
                  <b-dropdown-item href="#">ES</b-dropdown-item>
                  <b-dropdown-item href="#">RU</b-dropdown-item>
                  <b-dropdown-item href="#">FA</b-dropdown-item>
                </b-nav-item-dropdown>

                <b-nav-item-dropdown right>
                  <template #button-content>
                    <em>User</em>
                  </template>
                  <b-dropdown-item href="#">Profile</b-dropdown-item>
                  <b-dropdown-item href="#">Sign Out</b-dropdown-item>
                </b-nav-item-dropdown>
              </b-navbar-nav>
            </b-collapse>
          </b-navbar>
        </b-row>
      </b-container>
    </div>
  </div> -->
  <div class="nav mx-auto my-auto m-auto d-flex">
    <b-container class="pl-0 pr-0"> 
      <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
          <b-navbar-brand href="#">NavBar</b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="items">
              <b-nav-item class="item" href="#solicita_info">MBA Online</b-nav-item>
              <b-nav-item class="item" href="#ranking">Ranking</b-nav-item>
              <b-nav-item class="item" href="#director_pala">Palabras <br> del Director</b-nav-item>
              <b-nav-item class="item" href="#porque_mba">¿Por qué el MBA <br> Semipresencial <br> De ESAN?</b-nav-item>
              <b-nav-item class="item" href="#se_parte">Sé parte del <br> MBA <br> Semipresencial</b-nav-item>
              <b-nav-item class="item" href="#beneficios">Beneficios</b-nav-item>
              <b-nav-item class="item" href="#porque_esan">¿Por qué un <br>MBA en ESAN?</b-nav-item>              
            </b-navbar-nav>

         
          </b-collapse>
        </b-navbar>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "HeaderPage",
};
</script>

<style lang="stylus" scoped>
@import '../styles/main.styl';
.bg-info
  background-color: #252a2d  !important;
// .navbar-expand-md 
.navbar-collapse
  justify-content center !important
  // padding-right 140px
.nav-w
  display flex 
  justify-content: space-between;
// .navbar-brand
//   max-width 254px
//   width 100%
  // background-image url("../assets/components/header/logo/logo.png")
.navbar.navbar-dark.bg-dark 
  background-color: bg-header;
.line
  border-right: 1px solid white;
  margin: auto;
  height 15px
.item-nav
  padding-right 15px
  padding-left 15px
  padding-top 10px
  font-family Raleway-Regular
.button-nav
  padding 10px 25px 10px 25px
  background-color primary-pee
  color black
  font-family gt-pressura-bold
  font-size 18px
.nav
  background-color bg-black !important
  padding 10px 0px
.router-link-active
  color #9F8F6C !important

.item 
  padding-left: 30px;
  text-align  center
.items 
  
  font-size: 13px;

</style>