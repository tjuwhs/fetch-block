all:
	govendor init
	govendor add +e
	govendor fetch -v +m
	go build -o blockTrigger

clean:
	rm -rf ./vendor
	rm -f fetch-block
