<page>
  <actionBar title="Svelte Native webView" />
  <stackLayout class="p-20">
    <webView src="<div>This works.</div>" />
    <webView src="~/demo.html" />
  </stackLayout>
</page>

<style>
  webView {
    border-width: 2;
    height: 100;
    margin-top: 10;
  }
</style>
