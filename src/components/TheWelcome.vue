<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconCH7HD.vue'
import ToolingIcon from './icons/IconMCOT.vue'
import EcosystemIcon from './icons/IconWorkpoint.vue'
import CommunityIcon from './icons/IconCH3HD.vue'
import SupportIcon from './icons/IconMono29.vue'

</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>ช่อง 7HD</template>

    กดตรงนี้เลย --- >
    <a href="https://www.ch7.com/live.html" target="_blank" rel="noopener">กดตรงนี้</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>ช่อง 9 อสมท</template>

    กดตรงนี้เลย --- >
    <a href="https://tv.mcot.net/index" target="_blank" rel="noopener">กดตรงนี้</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>ช่อง Workpoint</template>

    กดตรงนี้เลย --- >
    <a href="https://www.workpointtv.com/live-stream-page" target="_blank" rel="noopener">กดตรงนี้</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>ช่อง 3HD</template>

    กดตรงนี้เลย --- >
    <a href="https://ch3plus.com/live" target="_blank" rel="noopener">กดตรงนี้</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>ช่อง MONO29</template>

    กดตรงนี้เลย --- >
    <a href="https://mono29.com/livetv" target="_blank" rel="noopener">กดตรงนี้</a>
  </WelcomeItem>
</template>
