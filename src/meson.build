labwc_sources = files(
  'action.c',
  'buffer.c',
  'debug.c',
  'desktop.c',
  'dnd.c',
  'foreign.c',
  'idle.c',
  'interactive.c',
  'layers.c',
  'main.c',
  'node.c',
  'osd.c',
  'output.c',
  'regions.c',
  'resistance.c',
  'seat.c',
  'server.c',
  'session-lock.c',
  'snap.c',
  'theme.c',
  'view.c',
  'view-impl-common.c',
  'window-rules.c',
  'workspaces.c',
  'xdg.c',
  'xdg-popup.c',
)

if have_xwayland
  labwc_sources += files(
    'xwayland.c',
    'xwayland-unmanaged.c',
  )
endif


subdir('button')
subdir('common')
subdir('config')
subdir('decorations')
subdir('input')
subdir('menu')
subdir('ssd')
