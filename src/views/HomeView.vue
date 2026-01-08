<template>
  <div class="row row-cards">
    <div class="col-12">
      <div class="card">
        <div class="card-body">
          <h1 class="card-title">Vue + Tabler</h1>
          <p class="text-muted">
            已集成 Vue Router、Pinia 和 Tabler UI，后续可在此基础上扩展页面与组件。
          </p>
          <div class="d-flex align-items-center gap-2">
            <button class="btn btn-primary" type="button" @click="counter.increment">
              计数 +1
            </button>
            <span class="badge bg-azure">当前计数：{{ counter.count }}</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { useCounterStore } from '../stores/counter';

const counter = useCounterStore();
</script>
