-- ============================================================
-- JENNARA THEME — Hyprland config (Simple Minimalist / macOS Feel)
-- ============================================================

local activeTopBorder = {
  colors = { "rgb(255, 255, 255)", "rgba(255, 255, 255, 0)" },
  angle = 90,
}



hl.config({
  general = {
    -- Top Accent Line: Garis aksen ultra-tipis (1px hairline) di bagian atas jendela aktif
    border_size = 1,
    col = {
      active_border = activeTopBorder,
      inactive_border = "rgba(00000000)",
    },
    gaps_in = 6,
    gaps_out = 12,
  },


  -- Tab Window Grouping: macOS Segmented Capsule Bar
  group = {
    col = {
      border_active = "rgb(255, 255, 255)",
      border_inactive = "rgb(33, 33, 36)",
    },

    groupbar = {
      enabled = true,
      render_titles = true,
      gradients = true,              -- Latar tab 100% solid
      font_family = "Adwaita Sans",
      font_size = 11,
      height = 26,
      indicator_height = 0,
      indicator_gap = 0,
      rounding = 13,                 -- Bentuk kapsul melengkung di ujung luar bar
      gradient_rounding = 13,
      round_only_edges = true,       -- Bulatkan hanya ujung terluar bar
      gradient_round_only_edges = true,
      gaps_in = 0,                   -- Tanpa sela di tengah (menyatu seperti segmented bar)
      gaps_out = 4,                  -- Jarak sela melayang
      text_color = "rgb(255, 255, 255)",
      text_color_inactive = "rgba(255, 255, 255, 0.45)",
      col = {
        active = "rgb(26, 26, 29)",   -- Tab aktif: Hitam pekat solid (#1a1a1d)
        inactive = "rgb(54, 54, 62)", -- Tab inaktif: Abu-abu track Space Gray (#36363e)
      },
    },
  },

  decoration = {
    -- Sudut jendela membulat (rounded corners)
    rounding = 14,
    rounding_power = 2,

    -- Matikan peredupan: semua jendela tetap 100% terang
    dim_inactive = false,

    -- Soft & Natural Shadow Elevation (macOS style)
    shadow = {
      enabled = true,
      range = 12,
      render_power = 2,
      color = "rgba(00000035)",
      color_inactive = "rgba(00000000)",
    },

    -- Blur halus untuk elemen transparan
    blur = {
      enabled = true,
      size = 6,
      passes = 2,
      new_optimizations = true,
    },
  },
})
