<script>
	chrome.runtime.onMessage.addListener(function (request, sender, sendResponse) {
		if (request.message === 'TabUpdated') {
			// Tab has been updated

			// do something here
		}
	});
</script>