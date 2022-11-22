# Author: Janusz Lewandowski <lew21@xtreeme.org>
# Contributor: David McFarland <corngood@gmail.com>
# Maintainer: Andrew Shark <ashark @at@ linuxcomp.ru>
# Autogenerated from AMD's Packages file
# with https://github.com/Ashark/archlinux-amdgpu-pro/blob/master/gen-PKGBUILD.py

major=22.20.4
major_short=22.20
minor=1498766
ubuntu_ver=22.04

pkgbase=amdgpu-pro-installer
pkgname=(
amf-amdgpu-pro
amdgpu-pro-libgl
lib32-amdgpu-pro-libgl
vulkan-amdgpu-pro
lib32-vulkan-amdgpu-pro
)
pkgver=${major}_${minor}
pkgrel=2
arch=('x86_64')
url=https://www.amd.com/en/support/kb/release-notes/rn-amdgpu-unified-linux-22-20
license=('custom: multiple')
groups=('Radeon_Software_for_Linux')
makedepends=('wget')

DLAGENTS='https::/usr/bin/wget --referer https://www.amd.com/en/support/kb/release-notes/rn-amdgpu-unified-linux-22-20 -N %u'

source=(progl
	progl.bash-completion
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/a/amf-amdgpu-pro/amf-amdgpu-pro_1.4.26-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/liba/libamdenc-amdgpu-pro/libamdenc-amdgpu-pro_1.0-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libegl1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libegl1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/a/appprofiles-amdgpu-pro/libgl1-amdgpu-pro-appprofiles_${major_short}-${minor}~${ubuntu_ver}_all.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-dri_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-dri_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-ext_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-ext_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-glx_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgl1-amdgpu-pro-glx_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libglapi1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libglapi1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgles2-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/o/opengl-amdgpu-pro/libgles2-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/v/vulkan-amdgpu-pro/vulkan-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
	http://repo.radeon.com/amdgpu/${major}/ubuntu/pool/proprietary/v/vulkan-amdgpu-pro/vulkan-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb)
sha256sums=(feb74796c3152cbafaba89d96e68a152f209bd3058c7eb0413cbe1ab0764e96f
	e32801c38b475cd8df17a407726b86db3de26410f563d688325b4d4314fc5354
	0bb4703ee0aa60b46f116af9e683ed7542659a55ee9c92373b8572724cd78c90
	098ee65f8d1cf1ce3bf3b60d209a6ab4d82a8e1c1dda8dae07106ff1644ac2e5
	1ed23b6ee75e6ea7bf6c36045c2377ca0eb63475fdb2150863b64460b3122f56
	1aae17136c66034f655348d09e1524d80b513b3d619b3c48651b683c6153ba71
	b1d9d3df7bbadd349fc3c70c2b43d4a37b678c7c6adf79c8cdb851af5dd21f8f
	c67b2f5fef15f1a928d2727717c94dd6e722488f50c6f53abf79beafb211e965
	92e84826d94bfa9e98be5f0579a0b50978155ffb1f2540e1302b38aa6cc711c2
	cf7a36f31ee90e9e25285c3040801f64bbe9def431a29192fb652f33d6685b11
	a04166a9b07f60ed95ed5a7d662ad73956931217c7500e06eb034f5a228db756
	d1b4864c621ee02a22e9d674b5b9e59c0141aafd8494562ee0824f9f31dfaaf6
	4afae41c6e16c474f5c1b1539676467e05b464a84400a71d1f41f573aab917a7
	a7d9d2ac387deb4784d0ed177c68a17639cd6642867950cd954a8bcd80f15a53
	f645af92e65725ad9efdcb71a6c3ed6106e39a8f3c501b92ade186707d97b023
	b3719648af5da115e6904cf069aeb8f5131d2b6b089cdfae87091a2ab9ae5193
	27a02fa91525bfef5115c1804e893b180b1fce6309c476b31aaf31cf2cbdcf67
	67cdd1f739c264ec7503f46661e3110f1153b52a7d0807eff11bde101b50e903
	38fe7676c586049e7d62a5fb440d5167117245c8d59f1c1cf6849a3d2d366cd7)



# extracts a debian package
# $1: deb file to extract
extract_deb() {
    local tmpdir="$(basename "${1%.deb}")"
    rm -Rf "$tmpdir"
    mkdir "$tmpdir"
    cd "$tmpdir"
    ar x "$1"
    tar -C "${pkgdir}" -xf data.tar.xz
}
# move ubuntu specific /usr/lib/x86_64-linux-gnu to /usr/lib
# $1: debian package library dir (goes from opt/amdgpu or opt/amdgpu-pro and from x86_64 or i386)
# $2: arch package library dir (goes to usr/lib or usr/lib32)
move_libdir() {
    local deb_libdir="$1"
    local arch_libdir="$2"

    if [ -d "${pkgdir}/${deb_libdir}" ]; then
        if [ ! -d "${pkgdir}/${arch_libdir}" ]; then
            mkdir -p "${pkgdir}/${arch_libdir}"
        fi
        mv -t "${pkgdir}/${arch_libdir}/" "${pkgdir}/${deb_libdir}"/*
        find ${pkgdir} -type d -empty -delete
    fi
}
# move copyright file to proper place and remove debian changelog
move_copyright() {
    find ${pkgdir}/usr/share/doc -name "changelog.Debian.gz" -delete
    mkdir -p ${pkgdir}/usr/share/licenses/${pkgname}
    find ${pkgdir}/usr/share/doc -name "copyright" -exec mv {} ${pkgdir}/usr/share/licenses/${pkgname} \;
    find ${pkgdir}/usr/share/doc -type d -empty -delete
}

package_amf-amdgpu-pro () {
    pkgdesc="AMDGPU Pro Advanced Multimedia Framework"
    license=('custom: AMDGPU-PRO EULA')
    depends=("libdrm" "vulkan-amdgpu-pro=${major}_${minor}-${pkgrel}")
    optdepends=("rocm-opencl-runtime: Warning unspecified optdep description")

    extract_deb "${srcdir}"/amf-amdgpu-pro_1.4.26-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libamdenc-amdgpu-pro_1.0-${minor}~${ubuntu_ver}_amd64.deb
    move_libdir "opt/amdgpu-pro/lib/x86_64-linux-gnu" "usr/lib"
    move_copyright
}

package_amdgpu-pro-libgl () {
    pkgdesc="AMDGPU Pro OpenGL driver"
    license=('custom: AMDGPU-PRO EULA')
    provides=('libgl')
    depends=("libdrm" "libx11" "libxcb" "libxdamage" "libxext" "libxfixes" "libxxf86vm")
    backup=(etc/amd/amdapfxx.blb)

    extract_deb "${srcdir}"/libegl1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-appprofiles_${major_short}-${minor}~${ubuntu_ver}_all.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-dri_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-ext_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-glx_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libglapi1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    extract_deb "${srcdir}"/libgles2-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    move_copyright

    # extra_commands:
    move_libdir "usr/lib/x86_64-linux-gnu" "usr/lib"
    move_libdir "opt/amdgpu-pro/lib/x86_64-linux-gnu" "usr/lib/amdgpu-pro"
    move_libdir "opt/amdgpu-pro/lib/xorg" "usr/lib/amdgpu-pro/xorg"
    move_libdir "opt/amdgpu/share/drirc.d" "usr/share/drirc.d"
    sed -i "s|/opt/amdgpu-pro/lib/x86_64-linux-gnu|#/usr/lib/amdgpu-pro  # commented to prevent problems of booting with amdgpu-pro, use progl script|" "${pkgdir}"/etc/ld.so.conf.d/10-amdgpu-pro-x86_64.conf
    install -Dm755 "${srcdir}"/progl "${pkgdir}"/usr/bin/progl
    install -Dm755 "${srcdir}"/progl.bash-completion "${pkgdir}"/usr/share/bash-completion/completions/progl
    # For some reason, applications started with normal OpenGL (i.e. without ag pro) crashes at launch if this conf file is presented, so hide it for now, until I find out the reason of that.
    mv "${pkgdir}"/usr/share/drirc.d/10-amdgpu-pro.conf "${pkgdir}"/usr/share/drirc.d/10-amdgpu-pro.conf.hide
}

package_lib32-amdgpu-pro-libgl () {
    pkgdesc="AMDGPU Pro OpenGL driver (32-bit)"
    license=('custom: AMDGPU-PRO EULA')
    provides=('lib32-libgl')
    depends=("amdgpu-pro-libgl=${major}_${minor}-${pkgrel}" "lib32-libdrm" "lib32-libx11" "lib32-libxcb" "lib32-libxdamage" "lib32-libxext" "lib32-libxfixes" "lib32-libxxf86vm")
    backup=(etc/amd/amdrc etc/ld.so.conf.d/10-amdgpu-pro-i386.conf)

    extract_deb "${srcdir}"/libegl1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-dri_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-ext_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    extract_deb "${srcdir}"/libgl1-amdgpu-pro-glx_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    extract_deb "${srcdir}"/libglapi1-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    extract_deb "${srcdir}"/libgles2-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    move_copyright

    # extra_commands:
    rm "${pkgdir}"/etc/amd/amdrc "${pkgdir}"/opt/amdgpu-pro/lib/xorg/modules/extensions/libglx.so "${pkgdir}"/opt/amdgpu/share/drirc.d/10-amdgpu-pro.conf
    move_libdir "usr/lib/i386-linux-gnu" "usr/lib32"
    move_libdir "opt/amdgpu-pro/lib/i386-linux-gnu" "usr/lib32/amdgpu-pro"
    sed -i "s|/opt/amdgpu-pro/lib/i386-linux-gnu|#/usr/lib32/amdgpu-pro  # commented to prevent problems of booting with amdgpu-pro, use progl32 script|" "${pkgdir}"/etc/ld.so.conf.d/10-amdgpu-pro-i386.conf
}

package_vulkan-amdgpu-pro () {
    pkgdesc="AMDGPU Pro Vulkan driver"
    license=('custom: AMDGPU-PRO EULA')
    provides=('vulkan-driver')
    depends=("vulkan-icd-loader")
    optdepends=("openssl-1.1: Warning unspecified optdep description")

    extract_deb "${srcdir}"/vulkan-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_amd64.deb
    move_libdir "opt/amdgpu-pro/lib/x86_64-linux-gnu" "usr/lib"
    move_copyright

    # extra_commands:
    mkdir -p "${pkgdir}"/usr/share/vulkan/icd.d/
    mv "${pkgdir}"/opt/amdgpu-pro/etc/vulkan/icd.d/amd_icd64.json "${pkgdir}"/usr/share/vulkan/icd.d/amd_pro_icd64.json
    mv "${pkgdir}"/usr/lib/amdvlk64.so "${pkgdir}"/usr/lib/amdvlkpro64.so
    sed -i "s#/opt/amdgpu-pro/lib/x86_64-linux-gnu/amdvlk64.so#/usr/lib/amdvlkpro64.so#" "${pkgdir}"/usr/share/vulkan/icd.d/amd_pro_icd64.json
    find ${pkgdir} -type d -empty -delete
}

package_lib32-vulkan-amdgpu-pro () {
    pkgdesc="AMDGPU Pro Vulkan driver (32-bit)"
    license=('custom: AMDGPU-PRO EULA')
    provides=('lib32-vulkan-driver')
    depends=("lib32-vulkan-icd-loader")
    optdepends=("lib32-openssl-1.1: Warning unspecified optdep description")

    extract_deb "${srcdir}"/vulkan-amdgpu-pro_${major_short}-${minor}~${ubuntu_ver}_i386.deb
    move_libdir "opt/amdgpu-pro/lib/i386-linux-gnu" "usr/lib32"
    move_copyright

    # extra_commands:
    mkdir -p "${pkgdir}"/usr/share/vulkan/icd.d/
    mv "${pkgdir}"/opt/amdgpu-pro/etc/vulkan/icd.d/amd_icd32.json "${pkgdir}"/usr/share/vulkan/icd.d/amd_pro_icd32.json
    mv "${pkgdir}"/usr/lib32/amdvlk32.so "${pkgdir}"/usr/lib32/amdvlkpro32.so
    sed -i "s#/opt/amdgpu-pro/lib/i386-linux-gnu/amdvlk32.so#/usr/lib32/amdvlkpro32.so#" "${pkgdir}"/usr/share/vulkan/icd.d/amd_pro_icd32.json
    find ${pkgdir} -type d -empty -delete
}

