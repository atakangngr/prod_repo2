<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="500"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="597c1d71-91f3-4707-a382-1db596b726d5" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAspect src="https://i.imgur.com/LouhpWW.jpeg" tag="div" aspect="16:9"
        v-bind:aspects="[{'text':'4:3 (SD)','value':'4:3'},{'text':'1:1 (Square)','value':'1:1'},{'text':'16:9 (HD)','value':'16:9'},{'text':'1.85:1 (Widescreen)','value':'1.85:1'},{'text':'2:1 (Univisium/Superscope)','value':'2:1'},{'text':'21:9 (Anamorphic)','value':'21:9'},{'text':'1.43:1 (IMAX)','value':'1.43:1'},{'text':'3:2 (35mm Film)','value':'3:2'},{'text':'3:1 (APS-P)','value':'3:1'},{'text':'4/3 (Same as 4:3)','value':'4/3'},{'text':'16/9 (Same as 16:9)','value':'16/9'},{'text':'3 (Same as 3:1)','value':'3'},{'text':'2 (Same as 2:1)','value':'2'},{'text':'1.85 (Same as 1.85:1)','value':'1.85'},{'text':'1.5','value':'1.5'},{'text':'1 (Same as 1:1)','value':'1'}]"
        cardText="" bgVariant=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'src','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'CardText'}]}"
        v-bind:textVisibility="true" position="absolute" top="26.102448515551153%" left="29.657183021124155%"
        id="3be87b35-3f45-4a75-bcb0-32d8df5962af"
        v-bind:style="{'color':'#000000','width':'','fontSize':'8.556px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'left','background':'#ffffff','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'','paddingTop':'','visibility':'visible','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','textDecoration':'none','zIndex':2}"/>
      <WIconBreadcrumb rel="" href="" icon="house-fill" text="House" scale="" shift="" v-bind:active="false"
        v-bind:isIcon="true" v-bind:options="[]" v-bind:disabled="false" v-bind:selected="[]" v-bind:isEnabled="true"
        linkTarget="_self" visibility="visible" ariaCurrent="location" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute" top="35.09587213899371%"
        left="74.97236707020392%" id="e6eb97e9-f314-4d09-b652-27cb118fb099"
        v-bind:style="{'color':'#007bff','width':'','height':'','fontSize':'11.408px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'#e9ecef','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'7.13px','visibility':'visible','marginRight':'0px','paddingLeft':'7.13px','marginBottom':'0px','paddingRight':'7.13px','paddingBottom':'7.13px','textDecoration':'none','zIndex':3}"/>
      <WCarousel v-bind:fade="false" text="Text Content 1" ImgAlt="Blank Image 1" v-bind:noWrap="false"
        caption="Carousel 1" v-bind:noTouch="false" imageUrl="https://picsum.photos/500/250/?image=1082"
        v-bind:interval="5000" v-bind:isEnabled="true" background="" blankColor="#ababab" v-bind:indicators="false"
        secondText="Text Content 2" v-bind:noAnimation="false" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="17.43237156241552%" left="22.892612468976917%"
        id="9c43a7c9-703e-4158-a2bb-391648b7a648"
        v-bind:style="{'width':'356.5px','height':'178.25px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':4}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>