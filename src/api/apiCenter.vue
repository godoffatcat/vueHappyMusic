<script>
 export default {
     name: "ApiCenter",
     methods: {
        baseUrl = 'https://music-api.lujs.top',
        request(url, options) {
            var fullUrl = baseUrl + url
             return fetch(fullUrl, options).then((res) => {
                return res.json()
             })
            .catch(() => console.error('api错误，请检查是否输入正确'))
        },
        get(url, options) { 
            return request(url, {...options, method: 'GET'}) 
        }
}
 }
</script>
