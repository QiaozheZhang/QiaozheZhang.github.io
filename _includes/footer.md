<script>
document.addEventListener('click', function (e) {
  const btn = e.target.closest('.newbadges .newbadge[data-tab]');
  if (!btn) return;
  const wrap = btn.closest('.newbadges');
  const tab = btn.dataset.tab;
  wrap.dataset.open = (wrap.dataset.open === tab) ? '' : tab;
});
</script>
