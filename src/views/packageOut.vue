<template>
  <div>
    <h1>预约取件</h1>
    <a-form>
      <a-form-item label="运单号" :label-col="{span: 5}" :wrapper-col="{span: 12}">
        <a-input
          v-decorator="[
          'note',
          {rules: [{required: true, message: 'Please input your note!'}]}
        ]"
        />
      </a-form-item>
      <a-form-item label="取件时间" :label-col="{span: 5}" :wrapper-col="{span: 12}">
        <a-input
          v-decorator="[
          'note',
          {rules: [{required: true, message: 'Please input your note!'}]}
        ]"
        />
      </a-form-item>
    </a-form>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
export default {
  name: "packageOut",
  components: {
    HelloWorld
  }
}
</Script>