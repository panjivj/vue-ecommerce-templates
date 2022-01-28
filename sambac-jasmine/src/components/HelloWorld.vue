<template>
	<div>
		<el-row class="mb-4">
			<el-button>Default</el-button>
			<el-button type="primary">Primary</el-button>
			<el-button type="success">Success</el-button>
			<el-button type="info">Info</el-button>
			<el-button type="warning">Warning</el-button>
			<el-button type="danger">Danger</el-button>
			<el-button>中文</el-button>
		</el-row>
	</div>
</template>

<script setup></script>

<style scoped>
a {
	color: #42b983;
}
:root {
	--el-color-primary: #409eff;
	--el-color-success: #67c23a;
	--el-color-warning: #e6a23c;
	--el-color-danger: #f56c6c;
	--el-color-error: #f56c6c;
	--el-color-info: #909399;
}
</style>
