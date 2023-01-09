<template>
  <CRow>
    <CCol>
      <h1>PROGRESS HARIAN FUNGSIONAL</h1>
      <CCard class="mb-4"> </CCard>
      <CCard class="mb-4">
        <CCardHeader> INFORMASI IDENTITAS PEGAWAI </CCardHeader>
        <CCardBody>
          <div class="bd-example">
            <dl class="row">
              <dt class="col-sm-3">Nama Pegawai</dt>
              <dd class="col-sm-9">
                <p>Budianto</p>
              </dd>

              <dt class="col-sm-3">NIP</dt>
              <dd class="col-sm-9">
                <p>0123456789</p>
              </dd>

              <dt class="col-sm-3">Unit Kerja</dt>
              <dd class="col-sm-9">
                <p>Sub Keuangan</p>
              </dd>

              <dt class="col-sm-3">Satuan Kerja</dt>
              <dd class="col-sm-9">
                <dl class="row">
                  <dd class="col-sm-8">
                    <p>
                      Pusat Teknologi Informasi dan Pangkalan Data UIN Ar-Raniry
                    </p>
                  </dd>
                </dl>
              </dd>
            </dl>
          </div>
        </CCardBody>
      </CCard>
      <CCard class="mb-4">
        <CCardHeader> DATA PEKERJAAN HARIAN </CCardHeader>
        <CButton color="tambah" variant="outline">Tambah Pekerjaan</CButton>
      </CCard>
      <CCard>
        <CCardBody>
          <CForm>
            <CFormInput date="2022/2/16" label="Tanggal" ocale="id-INA" />
          </CForm>

          <CForm class="mt-2 mb-2">
            <label>BAB</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Pilih BAB Pekerjaan',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>
          <CForm class="mt-2 mb-2">
            <label>Sub-BAB</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Pilih Sub-BAB Pekerjaan',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>
          <CForm class="mt-2 mb-2">
            <label>Butir Pekerjaan</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Pilih Butir Pekerjaan',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>
          <CForm>
            <CFormInput
              type="deskripsi"
              id="exampleFormControlInput1"
              label="Deskripsi Pekerjaan"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm>
            <div class="mb-3">
              <CFormLabel for="formFile">Upload Bukti</CFormLabel>
              <CFormInput id="formFile" type="file" />
            </div>
          </CForm>
          <CForm>
            <CFormInput
              type="link"
              id="exampleFormControlInput1"
              label="Bukti Link"
              placeholder=""
              aria-describedby="exampleFormControlInputHelpInline"
            />
          </CForm>
          <CForm class="mt-2 mb-2">
            <label>Periode</label>
            <CFormSelect
              aria-label="Default select example"
              :options="[
                'Periode Progress',
                {
                  label: 'Ganjil 2023',
                  value: '1',
                },
                {
                  label: 'Genap 2023',
                  value: '2',
                },
              ]"
            >
            </CFormSelect>
          </CForm>
          <br />
          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
