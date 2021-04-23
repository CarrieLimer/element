<template>
  <div style="margin: 20px;">
	<div>
		<el-input v-model="input" placeholder="请输入内容"></el-input>
	</div>
	<div>
		<el-date-picker
			type="datetime"
			format="yyyy-MM-dd HH"
			v-model="dateValue"
		></el-date-picker>
	</div>
	<div>
		<el-date-picker
			type="datetimerange"
			format="yyyy-MM-dd HH"
			v-model="dateRangeValue"
		></el-date-picker>
	</div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
		input: 'Hello Element UI!',
		dateValue: new Date(),
		dateRangeValue:[new Date(),new Date()]
      };
    }
  };
</script>
