<template>
    <div>
<div class="header">
		<div class="header_c inner_c">
			<h1 class="logo">
				青竹商城
			</h1>
			<dl class = "allType">
				<dt><a href="#">查看所有类型</a></dt>
				<dd>
					<div class = "dd_inn">
						<ul class = "dd_cont">
							<li><a href="#">不锈钢</a></li>
							<li><a href="#">原料水泥</a></li>
							<li><a href="#">塑料</a></li>
							<li><a href="#">木质</a></li>
							<li><a href="#">陶瓷</a></li>
						</ul>
						<ul class="pro">
							<li>
								<a href="#">
									<div class="pic">
										<img src="./images/img25.png" alt="">
									</div>
									<div class="content">
										<h3>简约木质餐盘</h3>
										<span>￥200</span>
									</div>
								</a>
								<div class="mask">
									<a href="#" class = "btn">查看详情</a>
								</div>
							</li>
							<li>
								<a href="#">
									<div class="pic">
										<img src="./images/img26.png" alt="">
									</div>
									<div class="content">
										<h3>简约木质餐盘</h3>
										<span>￥200</span>
									</div>
								</a>
								<div class="mask">
									<a href="#" class = "btn">查看详情</a>
								</div>
							</li>
							<li>
								<a href="#">
									<div class="pic">
										<img src="./images/img27.png" alt="">
									</div>
									<div class="content">
										<h3>简约木质餐盘</h3>
										<span>￥200</span>
									</div>
								</a>
								<div class="mask">
									<a href="#" class = "btn">查看详情</a>
								</div>
							</li>
						</ul>
					</div>
				</dd>
			</dl>
			<ul class="nav">
                
				<li><a href="./index">首页</a></li>
				<li><a href="./allproducts">所有产品</a></li>
				<li><a href="./blog">博客</a></li>
				<li><a href="./article">文章列表</a></li>
			</ul>
			<a href="#" class="search"></a>
			<div class="reg">
				<div class="ico">
					<span class = "ico_c"></span>
					<div class="settle">
						<p class="con">0件商品 共计：<span>￥0</span></p>
						<a href="./shop" class="btn">结算</a>
					</div>
					<span class = "con">
						0
					</span>
				</div>

				<div class = "reg_c">
					<a href="./land" id="">登陆</a>
					<span>&nbsp;|&nbsp;</span>
					<a href="./registe">注册</a>
				</div>
			</div>
		</div>
	</div>
	<!-- header部分结束 -->
	<div class="login">
		<div class="main">
			<h2>登录</h2>
			<form action="#">
				<!-- 用户名 type属性值是text指的是文本框-->
				<input type="text" placeholder="手机/邮箱/用户名" class = "in1"  v-model="name">
				<!-- 密码 type属性值是password指的是密码框-->
				<input type="password" placeholder="登录密码" v-model="password">
				<!-- 注册和忘记密码 -->
				<p>
					<a href="#" class = "l">
						注册
					</a>
					<a href="#" class = "r">
						忘记密码
					</a>
				</p>
				<!-- input的type值如果是button，指的是按钮 -->
				<input type="button" value = "登陆" class = "btn_d" @click="login()">
				<input type="button" value = "用短信登陆" class = "btn_p">
			</form>
			<div class = "acc">
				<h3>社交账号登录</h3>
				<p>
					<a href="#" class = "a1"></a>
					<a href="#" class = "a2"></a>
					<a href="#" class = "a3"></a>
					<a href="#" class = "a4"></a>
					<a href="#" class = "a5"></a>
					<a href="#" class = "a6"></a>
				</p>
			</div>
		</div>
	</div>
	<!-- footer部分开始 -->
	<div class="footer">
		<div class="footer_c inner_c">
			<div class="footer_top">
				<div class="bir">
					<a href="#">
						<img src="./images/logo.png" alt="">
					</a>
					<div class="info">
						青竹良品原创生活类电商品牌，秉承一贯的严谨态度，我们深入世界各地，从源头全程严格把控商品生产环节，力求帮消费者甄选到最优质的商品，全线采用天然原材料，控制甲醛低量无害，采用进口工艺，国际生产线不断优化，食材保证核心原产地新鲜直供，让你享受品质生活
					</div>
				</div>
				<div class="about">
					<dl>
						<dt>
							<a href="#">
								关于我们
							</a>
						</dt>
						<dd>
							<a href="#">
								我的品牌
							</a>
						</dd>
						<dd>
							<a href="#">
								公司动态
							</a>
						</dd>
						<dd>
							<a href="#">
								经历发展
							</a>
						</dd>
						<dd>
							<a href="#">
								商品推广
							</a>
						</dd>
					</dl>
					<dl>
						<dt>
							<a href="#">
								关于我们
							</a>
						</dt>
						<dd>
							<a href="#">
								我的品牌
							</a>
						</dd>
						<dd>
							<a href="#">
								公司动态
							</a>
						</dd>
						<dd>
							<a href="#">
								经历发展
							</a>
						</dd>
						<dd>
							<a href="#">
								商品推广
							</a>
						</dd>
					</dl>
					<dl>
						<dt>
							<a href="#">
								关于我们
							</a>
						</dt>
						<dd>
							<a href="#">
								我的品牌
							</a>
						</dd>
						<dd>
							<a href="#">
								公司动态
							</a>
						</dd>
						<dd>
							<a href="#">
								经历发展
							</a>
						</dd>
						<dd>
							<a href="#">
								商品推广
							</a>
						</dd>
					</dl>
				</div>
				<div class="ewm">
					<p class="wx">
						<img src="./images/img71.png" alt="">
						<span>微信公众号</span>
					</p>
					<p class="wb">
						<img src="./images/img72.png" alt="">
						<span>微博公众号</span>
					</p>
				</div>
			</div>
		</div>
		<div class="footer_bar">
			<div class="footer_bar_c inner_c">
				<div class = "pay">
					<p class = "copy">
						2019 © youhaosuda.com
					</p>
					<p class = "ico">
						<a href="#">
							<img src="./images/img81.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img82.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img83.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img84.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img85.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img86.png" alt="">
						</a>
						<a href="#">
							<img src="./images/img87.png" alt="">
						</a>
					</p>
				</div>
				<div class="super">
					<a href="#" class = "pic1">
						
					</a>
					<a href="#" class = "pic2">
						
					</a>
					<a href="#" class = "pic3">
						
					</a>
				</div>
			</div>
		</div>
	</div>
	<!-- 返回顶部 -->
	<div class="lingpin_top">
		<a href="#" class = "qq">QQ<br/>客服</a>
		<a href="#" class = "wx">微信<br/>客服</a>
		<a href="#" class = "top_c">↑</a>
	</div>
    </div>
</template>

<script>
import axios from 'axios'

    export default {
        data() {
			return {
				name:'',
				password:'',
			}
		},
		
		methods: {
			login(){
				console.log(111);
				axios({
				method:'post',
				url:this.globalAPI.login,
				data:{
					userName:this.name,
					password:this.password,
				},
			}).then(ref=>{
				if(ref.status==200){
					if(ref.data.code!=0){
						this.$notify.error({
						title: '错误',message: ref.data.msg});
					}
				console.log(ref)
				sessionStorage.setItem('accesstoken',ref.data.data.token)
				this.$router.push('/allproducts')
				}
			}).catch((error)=> { // 请求失败处理
				console.log(error)})
			}
			
		},
    }
</script>

<style scoped>
@import '../assets/common.css';
@import '../assets/reset.css';
@import '../assets/login.css';
</style>