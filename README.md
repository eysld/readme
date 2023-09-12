# 나의것
## 김지원
### 자바

---
***호호호***

package kr.couple.web.controller;

import org.springframework.stereotype.Controller;
import org.springframework.ui.Model;
import org.springframework.web.bind.annotation.GetMapping;

@Controller
public class homeController {
	@GetMapping(value = "/member/calendar")
	public String fullCalendarEx09(Model model) {
		return "/member/calendar";
	}
}
