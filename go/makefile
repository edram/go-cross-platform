android:
	go get golang.org/x/mobile/bind
	GOARCH=amd64 gomobile bind -v -trimpath -ldflags="-s -w" -o ./test.aar -target=android ./sdk/
	go mod tidy