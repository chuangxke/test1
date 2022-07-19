/home/acrn/Documents/GitHub/acrn-hypervisor/misc/config_tools/configurator/packages/configurator/src/pages/Config/ConfigForm/CustomWidget/CAT.vue
:disabled="SSRAM_ENABLED==='y'||VCAT_ENABLED==='y'||CDP_ENABLED==='y'"
            @click="(event)=>checkboxController('CDP_ENABLED',event)">
