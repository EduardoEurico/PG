package q4

import "fmt"

func ClassifyPrices(prices []int) (int, error) {
	if len(prices) == 0{
		return 0, fmt.Errorf("lista inválida")
	}
	if len(prices) == 1 {
		return 3, nil
	}
	var crescente bool = true
	var decrescente bool = true
	for i:= 1; i < len(prices); i++{
		if prices[i] < prices[i-1]{
			crescente = false
		} else if prices[i] > prices[i-1] {
			decrescente = false
		}
		
	}
	if crescente == true{
		return 1, nil
	} else if decrescente == true{
		return 2, nil
	}else{
		return 3, nil
	}
	return 0, nil
}
