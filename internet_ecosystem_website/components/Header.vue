<template>
  <header class="py-10 mx-auto bg-green-100 flex">
    <nav>
      <ul style="list-style:none;font-size:30px;">
        <li style="display:inline;left:50px;position:relative;top:40px">
          <nuxt-link
            class="hover:underline"
            style="color:#7bb062"
            to="/">
            <strong>Home</strong>
          </nuxt-link>
        </li>
        <li style="display:inline;left:170px;position:relative;top:40px">
          <nuxt-link
            class="hover:underline"
            style="color:#7bb062"
            to="/company-search">
            <strong>Company Search</strong>
          </nuxt-link>
        </li>
      </ul>
    </nav>
    <div class="flex-1">
      <a href="/" class="block w-56 mx-auto">
        <img width=150px height=150px style="position:relative; left:70px" src="./internet_ecosystem_logo.png">
      </a>
    </div>
    <nav>
      <ul style="list-style:none;font-size:30px;">
        <li style="display:inline;right:150px; margin:50px;position:relative;top:40px">
          <nuxt-link
            class="hover:underline"
            style="color:#7bb062"
            to="/browser-extension">
            <strong>Browser Extension</strong>
          </nuxt-link>
        </li>
        <li style="display:inline;right:60px;position:relative;top:40px">
          <nuxt-link
            class="hover:underline"
            style="color:#7bb062"
            to="/faqs">
            <strong>FAQs</strong>
          </nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>
