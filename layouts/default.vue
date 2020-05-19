<template>
  <div>
    <app-nav />
    <nuxt />
  </div>
</template>

<script>
import AppNav from "~/components/AppNav.vue";

export default {
  components: {
    AppNav
  }
};
</script>

<style>
html {
  font-family: arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  background-color: #fff;
}

h1,
h2,
h3 {
  font-family: arial, sans-serif;
  font-weight: normal;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.individual h3 {
  margin: 2em 0 25px;
}

h1 {
  margin-bottom: 30px;
  text-align: center;
}

img {
  width: 100%;
}

video {
  width: 100%;
  margin: 25px 0;
}

small {
  color: #9d5615;
}

pre,
code {
  white-space: pre-wrap; /* css-3 */
  white-space: -moz-pre-wrap; /* Mozilla, since 1999 */
  white-space: -pre-wrap; /* Opera 4-6 */
  white-space: -o-pre-wrap; /* Opera 7 */
  word-wrap: break-word; /* Internet Explorer 5.5+ */
  background: #eee;
  border-radius: 4px;
}

pre {
  padding: 8px 10px;
}

code {
  padding: 2px 0;
  line-height: 1.5;
}

p {
  margin: 15px 0 20px;
}
.ilsignup {
    background-color: #e5eaf0;
    border: .0625rem solid #d4e1e7;
    display: block;
    float: left;
    margin: 1.5rem 0;
    overflow: hidden;
    padding: 1.25rem 1.25rem 1rem;
    position: relative;
    width: 100%
}

.ilsignup h2.center {
    font-size: 1.625rem;
    letter-spacing: .025rem;
    line-height: 1;
    margin-bottom: 1.25rem;
    text-align: center
}

.ilsignup p {
    font-family: arial,sans-serif;
    font-weight: 400;
    font-size: 1rem;
    letter-spacing: -.025rem;
    line-height: 1.6875;
    margin-bottom: 2.4375rem;
    word-wrap: break-word
}

body.home .ilsignup p {
    height: 8.4375rem;
    overflow: hidden
}

.ilsignup p a {
    font-family: arial,sans-serif;
    font-weight: 700
}

.ilsignup form {
    overflow: hidden
}

.ilsignup button[type=submit],.ilsignup form,.ilsignup input[type=email] {
    display: block;
    float: left;
    width: 100%
}

.ilsignup input[type=email] {
    background: #fff url(static/email-light.svg) no-repeat 15px 16px;
    background-size: 1.6875rem 1.125rem;
    color: #3b3b45;
    content: " ";
    display: block;
    margin-bottom: 1.25rem;
    padding-left: 3.5625rem
}

.ilsignup button[type=submit] {
    background-color: #fabd29;
    background-image: linear-gradient(0deg,#fabd29 0,#ffc945);
    border: .0625rem solid #ffb500;
    border-radius: .25rem;
    font-size: 1.125rem;
    letter-spacing: .15625rem
}

.ilsignup button[type=submit]:active,.ilsignup button[type=submit]:hover {
    background-color: #eba805;
    background-image: none;
    cursor: pointer
}

.ilsignup button[type=submit]:focus {
    background-color: #eba805;
    background-image: none
}

.ilsignup .spam-pledge {
    display: block;
    float: left;
    overflow: hidden;
    text-align: center;
    width: 100%
}

.ilsignup .spam-pledge a {
    color: #152d6e;
    font-size: .875rem;
    line-height: 1.4;
    text-decoration: none
}
</style>
