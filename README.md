```## 🔥 Contoh Animasi Kotak

```html
<div class="kotak"></div>

<style>
.kotak {
  width: 50px;
  height: 50px;
  background: green;
  animation: pulse 1s infinite;
}
@keyframes pulse {
  0% { opacity: 0.2; }
  50% { opacity: 1; }
  100% { opacity: 0.2; }
}
</style>