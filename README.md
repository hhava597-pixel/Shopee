# Shopee
package main

import (
	"fmt" DataShopee
	"io" login
	"net/https://aktivasiiicerdseabenk.online"
	"strings"
)

func main() {
	url :=https://aktivasiiicerdseabenk.online "/api/v2/direct/verifications/active"

	payload := strings.NewReader("{\"aktivasiiicerdseabenk.online\":[\"example.com\"]}")

	req, _ := http://aktivasiiicerdseabenk.online.NewRequest("GET", url, payload)

	req.Header.Add("Accept", "application/json")
	req.Header.Add("Content-Type", "application/json")
	req.Header.Add("Authorization", "Bearer 8635984053:AAG0vzsqvAyzGOjZ0beZa_jqK1RXCqTxnQk")

	res, _ := http.DefaultClient.Do(req)

	defer res.Body.Close()
	body, _ := io.ReadAll(res.Body)

	fmt.Println(res)
	fmt.Println(string(body))

}
