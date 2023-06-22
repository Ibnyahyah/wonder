<script setup lang="ts">
import Arrow from '@/components/icons/arrow.vue'
import Resume from '@/components/icons/resume.vue'
import wonder from '@/components/icons/wonder.vue'
import gmail from '@/components/icons/gmail.vue'
</script>

<template>
  <main>
    <div class="row">
      <div class="card">
        <div class="row">
          <wonder />
          <div>
            <p>A product designer</p>
            <h2>Adewuyi wonder</h2>
            <p>I’m a creative product designer, Committed to simplifying life through design.</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="row">
          <Resume />
          <div>
            <h2>Resume</h2>
            <p>I’m a creative product designer, Committed to simplifying life through design.</p>
            <arrow />
          </div>
        </div>
      </div>
      <div class="card">
        <div class="row">
          <wonder />
          <div>
            <p>A product designer</p>
            <h2>Adewuyi wonder</h2>
            <p>I’m a creative product designer, Committed to simplifying life through design.</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="row">
          <wonder />
          <div>
            <h2>My Portfolio</h2>
            <p>https://www.behance.net/<br />adewuyiwonder</p>
            <arrow />
          </div>
        </div>
      </div>
      <div class="card">
        <div class="row">
          <div>
            <h2>Let's Connect</h2>
            <div class="row">
              <gmail />
              <p>Adewuyiwonder1@gmail.com</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.row:not(.card .row) {
  display: flex;
  align-items: center;
  gap: 10px;
  flex-wrap: wrap;
  justify-content: center;
}

.card .row {
  display: flex;
  gap: 20px;
}
.card {
  background: var(--linear-color);
  border: 2.5px solid #393939;
  border-radius: 20px;
  width: 31.4%;
  padding: 10px 20px;
  height: 200px;
  display: flex;
  align-items: center;
}
.card:last-child {
  width: calc(31.6% * 2);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.card p:first-child {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: 500;
  line-height: 22px;
}
.card .row div:last-child {
  width: 90%;
}
.card h2 {
  margin: 10px 0;
  font-size: 20px;
  font-weight: 700;
  line-height: 32px;
}
.card p:last-child {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: 500;
  line-height: 17px;
}
</style>
