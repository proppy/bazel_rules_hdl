# Copyright 2020 Google LLC
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Empty BUILD file, just to make this directory a Bazel package.

load("@rules_pkg//:pkg.bzl", "pkg_tar")

pkg_tar(
    name = "dist",
    extension = "tar.gz",
    srcs = [
        "@at_clifford_yosys//:yosys",
        "@org_theopenroadproject//:openroad",
        "@org_theopenroadproject//:opensta",
        "@com_icarus_iverilog//:iverilog",
        "@com_icarus_iverilog//:vvp",
        "@net_sourceforge_ngspice//:ngspice",
        "@edu_berkeley_abc//:abc",
        "@com_github_yosyshq_nextpnr//:nextpnr-generic",
        "@com_opencircuitdesign_magic//:magic",
        "@com_opencircuitdesign_magic//:ext2spice",
        "@com_opencircuitdesign_magic//:ext2hier",
        "@com_opencircuitdesign_magic//:ext2sim",
        "@com_opencircuitdesign_magic//:finds",
        "@com_opencircuitdesign_magic//:sim2simp",
        "@com_opencircuitdesign_magic//:extcheck",
        "@com_opencircuitdesign_magic//:net2ir",
        "@com_opencircuitdesign_netgen//:netgen",
        "@com_opencircuitdesign_netgen//:netcomp",
        "@com_opencircuitdesign_netgen//:ntk2adl",
        "@com_opencircuitdesign_netgen//:ntk2xnf",
    ],
    strip_prefix = "./external",
)
