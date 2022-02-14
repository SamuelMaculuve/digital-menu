<template>
  <div class="restbeef_site_wrapper fadeOnLoad">
    <!-- Content -->
    <div class="restbeef_main_wrapper restbeef_no_top_padding restbeef_no_bottom_padding">
      <div class="restbeef_container">
        <div class="restbeef_content_wrapper restbeef_no_sidebar">
          <!-- Content Inner -->
          <div class="restbeef_content">
            <div class="restbeef_tiny">
              <!-- Steaks Menu Block -->
              <steaks-menu-block></steaks-menu-block>
              <!-- Grill Menu Block -->
              <!-- .restbeef_menu_block -->
              <grill-menu-block></grill-menu-block>
              <!-- Salads Menu Block -->
              <salads-menu-block></salads-menu-block>
            </div><!-- .restbeef_tiny -->
          </div><!-- .restbeef_content -->

        </div><!-- .restbeef_content_wrapper -->
      </div><!-- .restbeef_container -->
    </div><!-- .restbeef_main_wrapper -->

  </div><!-- .restbeef_site_wrapper -->
</template>

<script>
import SteaksMenuBlock from '@/components/Home/SteaksMenuBlock.vue'
import GrillMenuBlock from '@/components/Home/GrillMenuBlock.vue'
import SaladsMenuBlock from '@/components/Home/SaladsMenuBlock.vue'
export default {
  name: 'Home',
  components: {
    SteaksMenuBlock,
    GrillMenuBlock,
    SaladsMenuBlock
  }
}
</script>
