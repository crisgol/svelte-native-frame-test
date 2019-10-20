<page>
    <actionBar title="Test FRAME" icon="" flat="true">
        
        
    </actionBar>
    <gridLayout rows="300,*" columns="*">
        <gridLayout row="0" rows="50, 70, auto, auto,auto,auto,auto" columns="200, * ">

         
            <button text="Frame" on:tap="{showFrame}" col="0" row="1" />

        </gridLayout>

       
    </gridLayout>


   
</page>

<script>
    import {showModal, navigate,navigateTo, navigateBack } from "svelte-native"
   

    import DetailPage from "./DetailPage.svelte"
    
  

    function showFrame() {
        navigate({
            page: DetailPage,
            frame:"detail-page-frame"
        })
    }
    
</script>