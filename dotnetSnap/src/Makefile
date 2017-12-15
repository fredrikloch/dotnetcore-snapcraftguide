all: build

build:
	@dotnet publish --self-contained -o bin/publish \
	-c Release --runtime ubuntu.16.04-x64 
install:
	@mkdir -p $(DESTDIR)/bin
	@cp -r bin/publish $(DESTDIR)/bin/
clean:
	@rm -rf bin