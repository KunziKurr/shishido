<template>
  <header class="header">
    <div class="header_container">
      <div class="header_container_sub1">
        <h1 class="header_container_sub1_name">
          SHISHIDO
        </h1>
      </div>
      <div class="header_container_sub2">
        <div class="header_container_sub2_s1">
          <div class="header_container_sub2_s1_socials">
            <svg height="25" width="25" id="icon-facebook" viewBox="0 0 20 20">
              <path d="M17 1h-14c-1.1 0-2 0.9-2 2v14c0 1.101 0.9 2 2 2h7v-7h-2v-2.475h2v-2.050c0-2.164 1.212-3.684 3.766-3.684l1.803 0.002v2.605h-1.197c-0.994 0-1.372 0.746-1.372 1.438v1.69h2.568l-0.568 2.474h-2v7h4c1.1 0 2-0.899 2-2v-14c0-1.1-0.9-2-2-2z"></path>
            </svg>
              <svg height="25" width="25" id="icon-facebook" viewBox="0 0 20 20">
                <path d="M17.316 6.246c0.008 0.162 0.011 0.326 0.011 0.488 0 4.99-3.797 10.742-10.74 10.742-2.133 0-4.116-0.625-5.787-1.697 0.296 0.035 0.596 0.053 0.9 0.053 1.77 0 3.397-0.604 4.688-1.615-1.651-0.031-3.046-1.121-3.526-2.621 0.23 0.043 0.467 0.066 0.71 0.066 0.345 0 0.679-0.045 0.995-0.131-1.727-0.348-3.028-1.873-3.028-3.703 0-0.016 0-0.031 0-0.047 0.509 0.283 1.092 0.453 1.71 0.473-1.013-0.678-1.68-1.832-1.68-3.143 0-0.691 0.186-1.34 0.512-1.898 1.861 2.285 4.644 3.787 7.781 3.945-0.064-0.277-0.097-0.564-0.097-0.861 0-2.084 1.689-3.773 3.774-3.773 1.086 0 2.067 0.457 2.756 1.191 0.859-0.17 1.667-0.484 2.397-0.916-0.282 0.881-0.881 1.621-1.66 2.088 0.764-0.092 1.49-0.293 2.168-0.594-0.506 0.758-1.146 1.422-1.884 1.953z"></path>
            </svg>
              <svg height="25" width="25" id="icon-facebook" viewBox="0 0 20 20">
                <path d="M17 1h-14c-1.1 0-2 0.9-2 2v14c0 1.101 0.9 2 2 2h14c1.1 0 2-0.899 2-2v-14c0-1.1-0.9-2-2-2zM9.984 15.523c3.059 0 5.538-2.481 5.538-5.539 0-0.338-0.043-0.664-0.103-0.984h1.581v7.216c0 0.382-0.31 0.69-0.693 0.69h-12.614c-0.383 0-0.693-0.308-0.693-0.69v-7.216h1.549c-0.061 0.32-0.104 0.646-0.104 0.984 0 3.059 2.481 5.539 5.539 5.539zM6.523 9.984c0-1.912 1.55-3.461 3.462-3.461s3.462 1.549 3.462 3.461-1.551 3.462-3.462 3.462c-1.913 0-3.462-1.55-3.462-3.462zM16.307 6h-1.615c-0.382 0-0.692-0.312-0.692-0.692v-1.617c0-0.382 0.31-0.691 0.691-0.691h1.615c0.384 0 0.694 0.309 0.694 0.691v1.616c0 0.381-0.31 0.693-0.693 0.693z"></path>
            </svg>
          </div>
          <div class="header_container_sub2_s2">
            <nav class="header_container_sub2_s2_nav">
              <ul class="header_container_sub2_s2_nav_ul">
                <li class="header_container_sub2_s2_nav_ul_li">SHOP</li>
                <li class="header_container_sub2_s2_nav_ul_li">CART</li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>

export default {
  name: 'HeaderSection',

}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Nunito:Reg@1&display=swap');
  .header{
    margin: 1.4rem;
    &_container{
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-direction: row;
      &_sub{
        &1{
          &_name{
                font-size: 1.3rem;
                color: #fff;
                letter-spacing: -0.5px;
                    margin-left: 1rem;
          }
        }
        &2{
          display: flex;
          justify-content: space-between;
          flex-direction: row;
          align-items: center;
          width: 50%;

          &_s1{
             display: flex;
          justify-content: space-between;
          flex-direction: row;
          align-items: center;
          width: 100%;
          &_socials{
                display: flex;
    row-gap: 1rem;
    column-gap: 1.4rem;
    fill: #fff;
    & svg{
         height: 2rem;
    width: 2rem;
    }
          }
          }
          &_s2{
            &_nav{
              &_ul{
           

                    list-style: none;
    display: flex;
    margin: unset;
    column-gap: 1rem;
    font-weight: 600;
                &_li{
                  color:#fff;
                  text-transform: uppercase;
                  font-size: 1.25rem;
                }
              }
            }
          }
        }
      }
    }
  }
</style>
