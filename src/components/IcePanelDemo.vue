<template>
  <ice-wrapper2 direction="left" visible>
    <ice-wrapper-item>
      <ice-panel title="标题1" style="width: 100%; height: 100%">
        这是一个面板1
      </ice-panel>
    </ice-wrapper-item>
     <ice-wrapper-item>
      <ice-panel title="标题2" style="width: 100%; height: 100%">
        这是一个面板2
      </ice-panel>
    </ice-wrapper-item>
  </ice-wrapper2>
</template>

<script setup lang="ts">
import { IcePanel, IceWrapper2, IceWrapperItem } from "saturn-ui";
import "saturn-ui/lib/theme-default/IceWrapper2.css";
import "saturn-ui/lib/theme-default/IcePanel1.css";
</script>
