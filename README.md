This is a special flatpak build of Clapper (https://github.com/Rafostar/clapper) for aarch64 systems.
The customization that has been done are:
- Added the following env variable by default:
	"--env=GST_GL_API=gles2",
        "--env=GST_CLAPPER_USE_PLAYBIN3=1",
        "--env=GSK_RENDERER=ngl"
- Removed from compilation:
	`glib-networking`
	`gstreamer-vaapi`
	*dvd* plugins
