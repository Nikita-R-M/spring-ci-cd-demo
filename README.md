@RestController
public class HelloController {
    @GetMapping("/api/hello")
    public String hello() {
        return "CI CD Demo!";
    }
}
