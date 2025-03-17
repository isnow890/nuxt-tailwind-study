<template>
  <main class="container mx-auto max-w-3xl p-4">
    <div class="text-2xl mb-6">Font size</div>

    <p class="text-xs">text-xs</p>
    <p class="text-sm">text-sm</p>
    <p class="text-base">text-base</p>
    <p class="text-lg">text-lg</p>
    <p class="text-xl">text-xl</p>
    <p class="text-2xl">text-2xl</p>
    <p class="text-3xl">text-3xl</p>
    <p class="text-4xl">text-4xl</p>
    <p class="text-5xl">text-5xl</p>
    <p class="text-6xl">text-6xl</p>
    <p class="text-7xl">text-7xl</p>
    <p class="text-8xl">text-8xl</p>
    <p class="text-9xl">text-9xl</p>

    <div class="text-2xl my-6">Font size (Responsive)</div>

    <p class="text-base md:text-lg lg:text-xl xl:text-2xl">
      This text changes size based on screen width. It starts at base size, becomes larger on medium
      screens (md: 768px+), even larger on large screens (lg: 1024px+), and largest on extra-large
      screens (xl: 1280px+).
    </p>

    <div class="mt-4 p-2 bg-gray-100 text-sm">
      <p>Resize your browser to see the text size change at different breakpoints:</p>
      <ul class="list-disc pl-5 mt-2">
        <li>Base: Default size (below 768px)</li>
        <li>md: 768px and up</li>
        <li>lg: 1024px and up</li>
        <li>xl: 1280px and up</li>
      </ul>
    </div>

    <div class="mt-4 border-2 border-gray-400 rounded-lg p-2 bg-gray-900 text-white">
      <p>Resize your browser to see the text size change at different breakpoints:</p>
      <ul class="list-disc pl-5 mt-2">
        <li>Base: Default size (below 768px)</li>
        <li>md: 768px and up</li>
        <li>lg: 1024px and up</li>
        <li>xl: 1280px and up</li>
      </ul>
    </div>

    <div class="text-2xl my-6">Line Height</div>
    <p class="text-sm/6 mb-4">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, quam nobis corporis eligendi
      omnis sequi porro, alias aut atque quae nemo vero deserunt sed saepe maiores fuga.
      Repellendus, placeat perferendis?
    </p>
    <p class="text-sm/7 mb-4">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, quam nobis corporis eligendi
      omnis sequi porro, alias aut atque quae nemo vero deserunt sed saepe maiores fuga.
      Repellendus, placeat perferendis?
    </p>
    <p class="text-sm/8 mb-4">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos, quam nobis corporis eligendi
      omnis sequi porro, alias aut atque quae nemo vero deserunt sed saepe maiores fuga.
      Repellendus, placeat perferendis?
    </p>

    <div class="text-2xl my-6">font-smoothing</div>
    <p class="">The quick brown fox jumps over the lazy dog.</p>
    <p class="antialiased">The quick brown fox jumps over the lazy dog.</p>

    <div class="text-2xl my-6">font-style</div>
    <p class="italic">Lorem ipsum dolor sit amet.</p>

    <div class="text-2xl my-6">font-weight</div>
    <p class="font-light">Lorem ipsum dolor sit amet.</p>
    <p class="font-normal">Lorem ipsum dolor sit amet.</p>
    <p class="font-medium">Lorem ipsum dolor sit amet.</p>
    <p class="font-bold">Lorem ipsum dolor sit amet.</p>
    <p class="font-black">Lorem ipsum dolor sit amet.</p>

    <div class="text-2xl my-6">font-stretch</div>

    <p class="font-stretch-extra-condensed">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-condensed">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-normal">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-expanded">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-extra-expanded">Lorem ipsum dolor sit amet.</p>

    <p class="font-stretch-50%">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-100%">Lorem ipsum dolor sit amet.</p>
    <p class="font-stretch-150%">Lorem ipsum dolor sit amet.</p>

    <div class="text-2xl my-6">letter-spacing</div>
    <p class="tracking-tight ...">The quick brown fox ...</p>
    <p class="tracking-normal ...">The quick brown fox ...</p>
    <p class="tracking-wide ...">The quick brown fox ...</p>

    <div class="text-2xl my-6">line-clamp</div>

    <article>
      <time>Mar 10, 2020</time>
      <h2>Boost your conversion rate</h2>
      <p class="line-clamp-3">
        Nulla dolor velit adipisicing duis excepteur esse in duis nostrud occaecat mollit incididunt
        deserunt sunt. Ut ut sunt laborum ex occaecat eu tempor labore enim adipisicing minim ad.
        Est in quis eu dolore occaecat excepteur fugiat dolore nisi aliqua fugiat enim ut cillum.
        Labore enim duis nostrud eu. Est ut eiusmod consequat irure quis deserunt ex. Enim laboris
        dolor magna pariatur. Dolor et ad sint voluptate sunt elit mollit officia ad enim sit
        consectetur enim.
      </p>
      <div>
        <img src="" />
        Lindsay Walton
      </div>
    </article>

    <div class="text-2xl my-6">line-spacing</div>
    <p class="text-base/6 ...">So I started to walk into the water...</p>
    <p class="text-base/7 ...">So I started to walk into the water...</p>
    <p class="text-base/8 ...">So I started to walk into the water...</p>

    <p class="text-2xl leading-6 ...">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque delectus sit magnam.
      Distinctio maiores exercitationem nam cumque illo cum dolore, quod, beatae, vel suscipit eaque
      ipsam. Quos quae voluptates molestias! Illo qui libero voluptatum, fuga voluptates quibusdam
      nihil recusandae vitae praesentium, perferendis eius tempora laudantium vero maiores maxime
      deserunt culpa nostrum minus. Est, in. Quibusdam, nobis illum! Aspernatur, impedit aliquid.
      Incidunt ipsam iusto maiores culpa. Vitae, a! Nemo magni aliquid reiciendis perferendis harum
      quasi ratione, atque accusantium at eius voluptas dolorem sunt! Quidem natus harum nam rerum
      tempora praesentium itaque. Excepturi esse autem doloribus fuga at dolores dolor animi
      debitis? Ullam corporis neque optio provident quasi tempora, eius debitis deleniti soluta
      facere amet alias quas mollitia consequatur temporibus nostrum. Harum. Culpa aliquid ex magnam
      sit error aspernatur, molestiae eveniet dolores dolorum dignissimos deleniti libero laudantium
      in veniam itaque. Incidunt, quod autem debitis dolorem officiis quo eaque voluptatibus qui
      totam repellat. Explicabo, numquam dolore aliquam beatae voluptatum temporibus corporis.
      Molestiae inventore facilis, quasi cupiditate dolores ea soluta sint. Dignissimos unde,
      dolores beatae magni culpa id officia! Placeat soluta facere ullam veritatis. Quas iste
      tempore sapiente corrupti nostrum unde hic ducimus voluptates fugiat explicabo ea nesciunt in,
      cum eaque optio voluptas officiis. Mollitia incidunt nulla laudantium quos autem ipsa magni
      voluptate suscipit? Perferendis modi hic quidem unde eveniet nostrum eos. Perspiciatis
      doloremque ex dolores reprehenderit! Provident ad suscipit magni pariatur fugit veniam, est,
      similique officia alias odit numquam praesentium, vero quo aspernatur.
    </p>

    <ul class="list-disc">
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
    </ul>

    <ul class="list-decimal">
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
      <li>Now this is a story all about how, my life got flipped-turned upside down</li>
    </ul>
  </main>
</template>

<script lang="ts" setup></script>

<style></style>
