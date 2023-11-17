# telebot
Telegram bot


cli man

go mod init github.com/Setiuss/telebot

go install github.com/spf13/cobra-cli@latest

cobra-cli init

cobra-cli add version

cobra-cli add telebot

go build -ldflags "-X="github.com/Setiuss/telebot/cmd.appVersion=v1.0.0

gofmt -s -w ./

go get

go build -ldflags "-X="github.com/Setiuss/telebot/cmd.appVersion=v1.0.1

./telebot start

read -s TELE_TOKEN

echo $TELE_TOKEN

export TELE_TOKEN