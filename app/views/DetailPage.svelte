<frame id="detail-page-frame">
	<page>
        <label text="Detail Page" />
        <button text="Close me" on:tap="{ () => closeModal('hi from modal') }" />
	</page>
</frame>
<script>
        import { closeModal } from 'svelte-native'
</script>