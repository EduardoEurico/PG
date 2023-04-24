package q5
import "strings"
func ProcessString(s string) string {
	result := ""

	for i := 0; i < len(s); i++ {
		if strings.Contains("AEIOUaeiou", string(s[i])) {

			s := strings.ReplaceAll(s, "a", "")
			s = strings.ReplaceAll(s, "e", "")
			s = strings.ReplaceAll(s, "i", "")
			s = strings.ReplaceAll(s, "o", "")
			s = strings.ReplaceAll(s, "u", "")
			s = strings.ReplaceAll(s, "A", "")
			s = strings.ReplaceAll(s, "E", "")
			s = strings.ReplaceAll(s, "I", "")
			s = strings.ReplaceAll(s, "O", "")
			s = strings.ReplaceAll(s, "U", "")
			s = strings.ToLower(s)
		}
		if strings.Contains("BCDFGHJKLMNPQRSTVWXYZbcdfghjklmnpqrstvwxyz", string(s[i])) {
			output := "." + strings.ToLower(string(s[i]))
			result += output
		}
	}
	return result
}
