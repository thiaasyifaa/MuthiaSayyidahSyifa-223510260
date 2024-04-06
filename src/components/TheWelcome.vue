<script setup lang="ts">
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
    <template #heading>Tentang Saya</template>
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswa di <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://sman1bangkinangkota.sch.id/" target="_blank" rel="noopener">SMAN 1 BANGKINANG KOTA</a>
    Saya Berasal dari Kabupaten Kampar ,Kecamatan Bangkinang Provinsi Riau
  </WelcomeItem>
  <hr />

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>History</template>

   Saya pernah volunteer sebagai pamong pada IT Funday Angkatan 2023, dan sedang menjadi Kakak Asuh 2023.

    <br />

  </WelcomeItem>
  
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>

    1. Foreign Language <br>
    2. Time Management <br>
    3. Problem Solving 
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: muthiasayyidahsyifa@student.uir.ac.id <br>
    Instagram : <a href="https://www.instagram.com/thiaasyifaa/" target="_blank">@thiaasyifaa </a
    > <br>
    WhatsApp : +6213-7868-7***
    
  </WelcomeItem>
</template>
