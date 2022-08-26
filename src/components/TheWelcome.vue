<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading> <h2> <b>About</b> </h2></template>

   <h4> Nama saya Muhammad Rafli Putra Perdana. Berbekal ilmu dari <br> <a href="https://smktarunabhakti.net//" target="_blank" rel="noopener noreferrer">SMK Taruna Bhakti</a> jurusan Rekayasa Perangkat Lunak, saya <br> ingin merasakan bekerja dengan orang yang sudah sangat ahli <br> dalam membuat web. </h4>
  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Java Script</li>
      <li>Figma</li>
      <li>Bootstrap</li>
    </ul>
  </WelcomeItem> -->

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading> <h2> <b>Study</b> </h2></template>

    <h4> 2020-2023</h4>
    <h4><a href="https://smktarunabhakti.net/" target="_blank" rel="noopener noreferrer">SMK Taruna Bhakti</a></h4>
    <h4>Rekayasa Perangkat Lunak</h4>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading> <h2><b>Contact</b></h2> </template>

    <h4> <img alt="" class="logo" src="@/assets/phone.svg" width="30" height="30" /> +62877-4839-8126</h4>
    <h4> <img alt="" class="logo" src="@/assets/mail.svg" width="30" height="30" /> rafliputra1227@gmail.com</h4>
    <h4> <img alt="" class="logo" src="@/assets/github.svg" width="30" height="30" />  <a href="https://github.com/RafliPutra666" target="_blank" rel="noopener noreferrer">https://github.com/RafliPutra666</a></h4>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading> <h2><b>Experience</b></h2> </template>

    <h4>Web hospital design</h4>
    <h4>Bootcamp WordPress</h4>
    <h4>Aplikasi kasir cafe</h4>

  </WelcomeItem>
</template>
