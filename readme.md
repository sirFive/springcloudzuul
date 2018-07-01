
##以api-member/开头的请求转发到service-member
##比如说：http://localhost:8764/api-member/getMember  和 http://localhost:8763/getMember 的请求结果相同
##/api-order/的请求同理


#后面添加了token所以 访问要添加token.
#比如：http://localhost:8764/api-member/getMember?token==1