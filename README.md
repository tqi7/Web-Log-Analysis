https://app.letsdefend.io/training/lesson_detail/web-log-analysis


Q4:How many web requests are made with "DELETE" method in total?

in cmd kali

```
cat http.log | awk '{print $8}' | grep -w DELETE | wc -l
```

get answer
