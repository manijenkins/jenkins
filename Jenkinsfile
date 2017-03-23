node ('windows_slave') {
	stage 'Checkout'
		checkout scm

	stage 'Build'
		echo "Hi This is Build"
	stage 'Test'
		echo "All tests are passed"
		exit 1
	stage 'upload'
		echo "Uploading content"

}
