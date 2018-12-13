# draw.io
http://draw.io

only test
	@Bean
	@LoadBalanced
	RestTemplate restTemplate() {
		return new RestTemplate();
	}

为何加了@LoadBalanced就有负载均衡能力了，进去发现@LoadBalanced并没有做什么
